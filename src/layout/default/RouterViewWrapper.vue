<template>
  <div class="router-view-wrapper">
    <div :class="$route.path !== '/home' ? 'router-view' : ''">
      <router-view />
    </div>
  </div>
</template>

<style lang="scss" scoped>
.router-view-wrapper {
  padding: 16px;
  flex: 1;
  .router-view {
    position: relative;
    min-height: calc(100vh);
    // box-shadow: 0 0 4px rgba(0, 2, 2, 3, 0.1);
  }
}
</style>
