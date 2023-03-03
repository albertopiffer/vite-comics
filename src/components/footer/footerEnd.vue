<template>
    <div class="footerEnd">
        <div class="container">
            <h4>SIGN-UP NOW</h4>
            <ul>
                <li>
                    FOLLOW US
                </li>
                <li>
                    <img src="../../img/footer-facebook.png" alt="">
                </li>
                <li>
                    <img src="../../img/footer-twitter.png" alt="">
                </li>
                <li>
                    <img src="../../img/footer-youtube.png" alt="">
                </li>
                <li>
                    <img src="../../img/footer-pinterest.png" alt="">
                </li>
                <li>
                    <img src="../../img/footer-periscope.png" alt="">
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.footerEnd {
    height: 110px;
    background-color: #303030;

    font-family: sans-serif;
}

.footerEnd .container {
    display: flex;
    justify-content: space-between;
    align-items: center;

    height: 100%;
}

.footerEnd h4 {
    color: white;

    padding: 15px;
    border: 2px solid #0282f9;
}

.footerEnd ul {
    display: flex;
    justify-content: space-between;
    align-items: center;

    gap: 20px;

    color: #0282f9;
    font-weight: 700;
}
</style>