<template>
    <div class="footerMain">
        <div class="container">
            <div class="links">
                <div>
                    <h4>DC COMICS</h4>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h4>SHOP</h4>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div>
                    <h4>DC</h4>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscription</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div>
                    <h4>SITES</h4>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <img src="../../img/dc-logo-bg.png" alt="">
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.footerMain {
    background-color: black;
    background-image: url("../../img/footer-bg.jpg");
    background-repeat: repeat;
    background-size: contain;
    height: 370px;
}

.footerMain .container {
    height: 100%;
    display: flex;
    justify-content: space-between;

    padding-top: 40px;

    font-size: 12px;
    color: grey;

    overflow: visible;
}

.footerMain .links {
    display: flex;
    justify-content: flex-start;
    gap: 30px;
}

.footerMain h4 {
    margin: 20px 0;
    font-size: 16px;
    color: white;
}
</style>