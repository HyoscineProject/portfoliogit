<template>
    <div>
        <gallery :images="images" :index="index" @close="index = null"></gallery>
        <div
                class="image"
                v-for="(image, imageIndex) in images"
                :key="imageIndex"
                @click="index = imageIndex"
                :style="{ backgroundImage: 'url(' + image + ')', width: '300px', height: '200px' }"
        ></div>
    </div>
</template>

<script>
    import VueGallery from 'vue-gallery';

    export default {
        data: function () {
            return {
                images: [
                    'https://hyoscine.org/portfolio393/assets/hall.JPG',
                    'https://hyoscine.org/portfolio393/assets/sanitizingflyer.png',
                    'https://hyoscine.org/portfolio393/assets/maskflyer.png',
                    'https://hyoscine.org/portfolio393/assets/sunset.JPG',
                    'https://hyoscine.org/portfolio393/assets/sphinx.jpg',
                    'https://hyoscine.org/portfolio393/assets/21.jpg',
                    'https://hyoscine.org/portfolio393/assets/jj.jpg',
                    'https://hyoscine.org/portfolio393/assets/kiss.gif',
                    'https://hyoscine.org/portfolio393/assets/faust.jpg',
                    'https://hyoscine.org/portfolio393/assets/8415_Glitch5.jpg',
                    'https://hyoscine.org/portfolio393/assets/anglespink.jpg',
                    'https://hyoscine.org/portfolio393/assets/binaryaurora.jpg',
                    'https://hyoscine.org/portfolio393/assets/dreamscape.jpg',
                    'https://hyoscine.org/portfolio393/assets/deluxe.jpg',
                    'https://hyoscine.org/portfolio393/assets/drinkme.jpg',
                    'https://hyoscine.org/portfolio393/assets/dropmotion.jpg',
                    'https://hyoscine.org/portfolio393/assets/entropy.jpg',
                    'https://hyoscine.org/portfolio393/assets/exit.jpg',
                    'https://hyoscine.org/portfolio393/assets/exitnode.jpg',
                    'https://hyoscine.org/portfolio393/assets/gateway.jpg',
                    'https://hyoscine.org/portfolio393/assets/void.jpg',
                    'https://hyoscine.org/portfolio393/assets/halo.jpg',
                    'https://hyoscine.org/portfolio393/assets/hauntology.jpg',
                    'https://hyoscine.org/portfolio393/assets/hope.jpg',
                    'https://hyoscine.org/portfolio393/assets/lofi.jpg',
                    'https://hyoscine.org/portfolio393/assets/menacingruin.jpg',
                    'https://hyoscine.org/portfolio393/assets/nostalgia.jpg',
                    'https://hyoscine.org/portfolio393/assets/parallax.jpg',
                    'https://hyoscine.org/portfolio393/assets/parallels.jpg',
                    'https://hyoscine.org/portfolio393/assets/pinksolitude.jpg',
                    'https://hyoscine.org/portfolio393/assets/retrospace.jpg',
                    'https://hyoscine.org/portfolio393/assets/skywalk.jpg',
                    'https://hyoscine.org/portfolio393/assets/snail.jpg',
                    'https://hyoscine.org/portfolio393/assets/split.jpg',
                    'https://hyoscine.org/portfolio393/assets/titanic.jpg',
                    'https://hyoscine.org/portfolio393/assets/treekyo.jpg',
                    'https://hyoscine.org/portfolio393/assets/twinpeaks.jpg',
                    'https://hyoscine.org/portfolio393/assets/unreality.jpg',
                    'https://hyoscine.org/portfolio393/assets/vice.jpg',
                    'https://hyoscine.org/portfolio393/assets/vividsunset.jpg',
                    'https://hyoscine.org/portfolio393/assets/framedinpink.jpg',
                ],
                index: null
            };
        },

        components: {
            'gallery': VueGallery
        },
    }
</script>

<style scoped>

    div {

    }


    .blueimp-gallery {

        /* background:
       #000;
       */

    }


    .image {
        float: left;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center center;
        border: 1px solid lightblue;
        margin: 5px;
        opacity: 90%;
        transition: opacity 0.5s;
        filter: grayscale(70%);
    }

    .image:hover {
        opacity: 100%;
        filter: none;
    }
</style>