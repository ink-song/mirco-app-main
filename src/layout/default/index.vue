<template>
  <div class="container">
    <leftSide />
    <RouterViewWrapper />
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import leftSide from "./leftSide.vue";
import RouterViewWrapper from "@/layout/default/RouterViewWrapper.vue";
export default defineComponent({
  components: {
    leftSide,
    RouterViewWrapper,
  },
  setup() {
    return {};
  },
});
</script>

<style lang="scss" scoped>
.container {
  display: flex;
}
</style>
