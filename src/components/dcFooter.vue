<script>
import footerNavbar from './footer/footerNavbar.vue'
import footerMain from './footer/footerMain.vue'
import footerEnd from './footer/footerEnd.vue'

export default {
    components: {
        footerNavbar,
        footerMain,
        footerEnd,
    }
}
</script>

<template>
    <footer>
        <footerNavbar />
        <footerMain />
        <footerEnd />
    </footer>
</template>

<style lang="scss"></style>
