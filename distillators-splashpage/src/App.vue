<script setup>
import SplashMessage from './components/SplashMessage.vue'
</script>

<template>
  <header>
    <img alt="distillators-logo" class="logo" src="./assets/distillators.svg" />

    <div class="wrapper">
      <SplashMessage />
    </div>
  </header>


</template>

<style scoped>
header {
  line-height: 1.5;
  justify-items: center;
  align-items: center;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
  width: 950px;
  max-width: 100%;
  height: auto;
}
</style>
