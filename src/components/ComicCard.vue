<template>

    <div class="comic-card">
        <img :src="thumbImg" alt="">
        <h5>{{ comicPrice }}</h5>
        <h5>{{ comicSeries }}</h5>
        <h5>{{ comicType }}</h5>
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

<style>

</style>