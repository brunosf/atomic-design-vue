<template>
  <div class="presentation">
    <SocialNetworks />

    <img
      class="banner"
      src="@/assets/images/presentation.svg"
      alt="Apresentação"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialNetworks } from '@/components/molecules'

export default defineComponent({
  components: {
    SocialNetworks
  }
})
</script>

<style lang="scss" scoped>
.presentation {
  position: relative;
  display: grid;
  justify-content: center;
  .banner {
    width: 80%;
    justify-self: center;
  }
  .social-networks {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%);
  }
}
</style>
