<template>
    <nav>
        <div class="container">
            <ul>
                <li>
                    <img src="../../img/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </li>
                <li>
                    <img src="../../img/buy-comics-merchandise.png" alt="">
                    <span>merchandise</span>
                </li>
                <li>
                    <img src="../../img/buy-comics-subscriptions.png" alt="">
                    <span>subscription</span>
                </li>
                <li>
                    <img src="../../img/buy-comics-shop-locator.png" alt="">
                    <span>comic shop locator</span>
                </li>
                <li>
                    <img src="../../img/buy-comics-subscriptions.png" alt="">
                    <span>dc power visa</span>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style lang="scss">
nav {
    height: 150px;
    background-color: #0282f9;

    display: flex;
    align-items: center;
}

nav ul {
    font-family: sans-serif;
    font-weight: 600;
    font-size: 14px;
    text-transform: uppercase;
    color: white;

    display: flex;
    justify-content: space-between;

    margin: 0 40px;
}

nav img {
    height: 60px;
}

nav li {
    display: flex;
    justify-content: space-between;
    align-items: center;

    gap: 15px;
}
</style>
