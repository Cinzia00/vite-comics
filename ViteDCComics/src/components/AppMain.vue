<template>
    <main>
        <div class="img-jumbo">
            <img src="/jumbotron.jpg" alt="">
        </div>
        <div class="main-content">
            <div class="container">
                <a class="button button-current-serie">CURRENT SERIE</a>
                <ul class="card">
                    <card v-for="(element, i) in list" :key="i" :title="element.series.toUpperCase()"
                        :thumb="element.thumb" />
                </ul>
                <div class="button-load">
                    <a class="button button-load-more">LOAD MORE</a>
                </div>
            </div>
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
            list: [
                {
                    "thumb": "/action comics.webp",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "/amrican-vampire-1976.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                {
                    "thumb": "/acquaman.jpeg",
                    "price": "$16.99",
                    "series": "Aquaman",
                    "type": "graphic novel"
                },
                {
                    "thumb": "/batgirl.webp",
                    "price": "$2.99",
                    "series": "Batgirl",
                    "type": "comic book"
                },
                {
                    "thumb": "/+.jpg",
                    "price": "$3.99",
                    "series": "+",
                    "type": "comic book"
                },
                {
                    "thumb": "/batman-beyond.jpg",
                    "price": "$2.99",
                    "series": "Batman Beyond",
                    "type": "comic book"
                },
                {
                    "thumb": "/batman_superman.webp",
                    "price": "$3.99",
                    "series": "Batman/Superman",
                    "type": "comic book"
                },
                {
                    "thumb": "/batman-superman-annual.jpg",
                    "price": "$4.99",
                    "series": "Batman/Superman Annual",
                    "type": "comic book"
                },
                {
                    "thumb": "/batman-the-joker-war-zone.webp",
                    "price": "$5.99",
                    "series": "Batman: The Joker War Zone",
                    "type": "comic book"
                },
                {
                    "thumb": "/Batman-three-jokers.jpg",
                    "price": "$6.99",
                    "series": "Batman: Three Jokers",
                    "type": "comic book"
                },
                {
                    "thumb": "/batman-white-knight.jpg",
                    "price": "$4.99",
                    "series": "Batman: White Knight Presents: Harley Quinn",
                    "type": "comic book"
                },
                {
                    "thumb": "/catwoman.webp",
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
@use '../partials/reset' as *;

.main-content {
    color: white;
    padding: 70px 0 20px;
}

main {
    background-color: #1C1C1C;

}

.container {
    position: relative;

    .button-current-serie {
        padding: 13px 35px;
        font-size: 25px;
        position: absolute;
        top: -100px;
    }

}

.img-jumbo {
    height: 365px;

    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: top;
    }

}

.card {
    display: flex;
    flex-wrap: wrap;
    gap: 25px;
}

.button {
    background-color: #0282F9;
    padding: 13px 65px;
    color: white;
    font-weight: bold;
    font-size: 12px;
}

.button-load {
    padding: 20px 0 10px;
    display: block;
    width: fit-content;
    margin: 0 auto;
}


</style>
  