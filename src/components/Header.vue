<template>
    <header>
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
    </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem 0;
        border: 1px solid red;

        img {
            width: 70px;
        }
    }

    nav > ul {
        list-style: none;
            
        li {
            display: inline-block;
            margin: 0 0 0 2rem;
            text-transform: uppercase;
        }
    }

</style>