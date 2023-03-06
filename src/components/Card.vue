<template>
    <li class="card">
        <img :src="thumb" alt="">
        <span> {{ series }} </span>
    </li>
</template>

<script>
export default {
    props: {
        series: String,
        thumb: String,
    }
}
</script>

<style lang="scss" scoped>
.card {
    padding: 20px;

    display: flex;
    flex-direction: column;
    align-items: flex-start;

    flex-basis: calc(100%/6);

    span {
        font-size: 16px;
        text-transform: uppercase;
        color: white;
    }
}
</style>