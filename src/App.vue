<script>
import dcHead from './components/dcHead.vue'
import dcMain from './components/dcMain.vue'
import dcFooter from './components/dcFooter.vue'

export default {
  components: {
    dcHead,
    dcMain,
    dcFooter,
  }
}
</script>

<template>
  <dcHead />
  <dcMain />
  <dcFooter />
</template>

<style lang="scss">
@use './style/main.scss';
</style>
