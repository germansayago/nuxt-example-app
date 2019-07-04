<template>
  <div class="container">
    <main-navigation></main-navigation>
    <nuxt />
  </div>
</template>

<script>
import MainNavigation from '../components/MainNavigation.vue'

export default {
  components: {
    MainNavigation
  }
}
</script>

<style>
.container-inner{
  max-width: 650px;
}
</style>
