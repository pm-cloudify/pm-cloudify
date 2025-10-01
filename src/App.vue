<template>
  <!-- main container -->
  <div class="main-container">
    <TheAside></TheAside>
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script setup>
import TheAside from './components/aside/TheAside.vue'
</script>

<style lang="scss" scoped>
.main-container {
  height: 100vh;
  width: 100vw;
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: flex-start;

  > aside {
    background-color: red;
    width: 300px;
    height: 100%;
  }

  > main {
    background-color: orange;
    width: 100%;
    height: 100%;
  }
}
</style>
