<template>
    <main>

        <div class="container">

            <div class="jumbo"></div>

            <ul>
                <Card v-for="(comic, i) in comics" :key="i" :series="comic.series" :thumb="comic.thumb" />
            </ul>

        </div>

    </main>
</template>

<script>

import Card from './Card.vue'

export default {
    components: {
        Card
    },
    data() {
        return {
            comics: [
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$3.99",
                    "series": "Batman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "https://static.dc.com/dc/files/default_images/4937_400x600.jpg?w=160",
                    "price": "$16.99",
                    "series": "Catwoman",
                    "type": "graphic novel"
                }
            ]
        }
    }

}

</script>

<style lang="scss" scoped>
main {
    // height: 130px;
    background-color: #1c1c1c;

    .jumbo {
        background-image: url('../img/jumbotron.jpg');
        background-repeat: no-repeat;
        background-size: cover;

        height: 400px;
    }

    ul {
        display: flex;
        flex-wrap: wrap;
        justify-content: flex-start;
    }
}
</style>
