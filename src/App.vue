<template>
  <div id="app">
    <AppNavigation />
    <router-view/>
  </div>
</template>

<style lang="scss">
</style>

<script>
import AppNavigation from '@/components/Navigation.vue'

export default {
  name: 'Main',
  components: {
    AppNavigation
  }
}
</script>