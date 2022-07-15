<template>
    <header>
        <div class="container d-flex justify-content-between align-items-center">
            <img src="../assets/img/dc-logo.png" alt="dc logo">
            <nav>
                <ul>
                    <li>Character</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shops</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    header {
        padding: 1rem 0;

        img {
            width: 70px;
        }
    }

    nav > ul {
        list-style: none;
        margin-bottom: 0;
            
        li {
            display: inline-block;
            margin: 0 0 0 2rem;
            text-transform: uppercase;
        }
    }

</style>