<template>
  <DefaultLayer />
</template>
<script lang="ts">
import { defineComponent } from 'vue'
import DefaultLayer from '@/layout/default/index.vue';
export default defineComponent({
  components: { DefaultLayer },
  setup() {
    console.log('sada')
  },
})
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
