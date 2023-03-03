<template>
    <header>
        <div class="container">

            <img src="../img/dc-logo.png" alt="">

            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </div>
    </header>
</template>

<script>
</script>

<style lang="scss" scoped>
header {
    height: 120px;
    background-color: white;

    display: flex;
    align-items: center;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.container img {
    height: 80px;
}

.container ul {
    display: flex;
    justify-content: space-between;
    gap: 30px;

    font-family: sans-serif;
    font-weight: 700;
    font-size: 14px;

    text-transform: uppercase;
}
</style>
