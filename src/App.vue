<template>
  <div id="app">
    <AppHeader/>
    <AppContent/>
    <AppFooter/>
  </div>
</template>

<script>
import AppHeader from './layout/AppHeader.vue'
import AppContent from './layout/AppContent.vue'
import AppFooter from './layout/AppFooter.vue'

export default {
  components: {
    AppHeader, AppContent, AppFooter
  }
}
</script>

<style>
#app {
  background: #ffffff;
}
</style>
