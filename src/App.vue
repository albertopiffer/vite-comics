<script setup>
import AppFooter from './components/dcFooter.vue'
import AppHeader from './components/dcHeader.vue'
import AppMain from './components/dcMain.vue'

export default {
  components: {
    AppFooter,
    AppHeader,
    AppMain,
  }
}
</script>

<template>
  <div>
    <AppHeader />
    <AppMain />
    <AppFooter />
  </div>
</template>

<style scoped></style>
