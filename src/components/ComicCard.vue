<template>
    <div class="comic-card">
        <a href="">
            <img :src="thumbImg" alt="">
            <p class="text-uppercase text-center">{{ comicSeries }}</p>
        </a>
    </div>

</template>

<script>
export default {

    props: {
        'thumbImg' : String,
        'comicPrice' : String,
        'comicSeries' : String,
        'comicType' : String,
    }
}
</script>

<style lang="scss">

    .comic-card{
        width: calc((100% - 1rem * 2 * 6) / 6);
        margin: 1rem;

        img {
            object-fit: cover;
            object-position: top;
            width: 100%;
            aspect-ratio: 1/1;
        }
        
        a {
            font-size: 0.9rem;
            text-decoration: none;
            color: white;
        }
    }


</style>