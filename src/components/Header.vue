<template>
    <header>
        <div class="container d-flex justify-content-between align-items-center">
            <img src="../assets/img/dc-logo.png" alt="dc logo">
            <nav>
                <ul>
                    <li v-for="(link, index) in navbarItems" :key="index" :class="{active : link.selected}">
                        <a :href="link.url">{{link.text}}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    data: function(){
        return{
            navbarItems : [
                {
                    'text' : 'Characters',
                    'url' : '#',
                    'selected' : false
                },
                
                {
                    'text' : 'Comics',
                    'url' : '#',
                    'selected' : true
                },

                {
                    'text' : 'Movies',
                    'url' : '#',
                    'selected' : false
                },

                {
                    'text' : 'TV',
                    'url' : '#',
                    'selected' : false
                },

                {
                    'text' : 'Games',
                    'url' : '#',
                    'selected' : false
                },

                {
                    'text' : 'Collectibles',
                    'url' : '#',
                    'selected' : false
                },
                
                {
                    'text' : 'Videos',
                    'url' : '#',
                    'selected' : false
                },

                {
                    'text' : 'Fans',
                    'url' : '#',
                    'selected' : false
                },

                {
                    'text' : 'News',
                    'url' : '#',
                    'selected' : false
                },

                {
                    'text' : 'Shops',
                    'url' : '#',
                    'selected' : false
                }
            ]
        }
    }
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