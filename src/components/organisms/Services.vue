<template>
  <div class="services">
    <Service
      title="Front end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex facilis, et voluptates explicabo dolor recusandae neque esse cum molestiae repudiandae laborum beatae incidunt ipsa? Tenetur aperiam exercitationem praesentium ratione velit?"
    />
    <Service
      title="Back end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex facilis, et voluptates explicabo dolor recusandae neque esse cum molestiae repudiandae laborum beatae incidunt ipsa? Tenetur aperiam exercitationem praesentium ratione velit?"
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex facilis, et voluptates explicabo dolor recusandae neque esse cum molestiae repudiandae laborum beatae incidunt ipsa? Tenetur aperiam exercitationem praesentium ratione velit?"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
