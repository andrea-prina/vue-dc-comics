<template>
    <header>
        <div class="container d-flex justify-content-between align-items-center">
            <img src="../assets/img/dc-logo.png" alt="dc logo">
            <nav>
                <ul>
                    <li><a href="">Character</a></li>
                    <li class="active"><a href="">Comics</a></li>
                    <li><a href="">Movies</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">Games</a></li>
                    <li><a href="">Collectibles</a></li>
                    <li><a href="">Videos</a></li>
                    <li><a href="">Fans</a></li>
                    <li><a href="">News</a></li>
                    <li><a href="">Shops</a></li>
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
@import "../style/variables.scss";

    header {
        

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
            border-bottom: 5px solid white;

            &.active, &:hover {
                border-bottom: 5px solid $brand-color;
            }
            
            &, a {
                padding: 2.5rem 0;
            }

            a {
                text-decoration: none;
                color: black;
                text-transform: uppercase;
            }

            &.active a, &:hover a {
                color: $brand-color;
            }

        }

    }

</style>