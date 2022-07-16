<template>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-4 pt-4 pb-4">
                    <div class="container-fluid p-0">
                        <div class="row">
                            <div class="col-4">
                                <h5>DC COMICS</h5>
                                <ul class="list-unstyled">
                                    <li v-for="(link, index) in dcComicsLinks" :key="index">
                                        <a :href="link.url">{{link.text}}</a>
                                    </li>
                                </ul>
                                <h5>SHOP</h5>
                                <ul class="list-unstyled">
                                    <li v-for="(link, index) in dcShopsLinks" :key="index">
                                        <a :href="link.url">{{link.text}}</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h5>DC</h5>
                                <ul class="list-unstyled">
                                    <li v-for="(link, index) in dcLinks" :key="index">
                                        <a :href="link.url">{{link.text}}</a>
                                    </li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h5>SITES</h5>
                                <ul class="list-unstyled">
                                    <li v-for="(link, index) in dcSitesLinks" :key="index">
                                        <a :href="link.url">{{link.text}}</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-8 position-relative overflow-hidden">
                    <img class="background-logo" src="../assets/img/dc-logo-bg.png" alt="DC background logo">
                </div>
            </div>
        </div>
    </footer>

</template>

<script>
export default {

    data: function(){
        return{

            dcComicsLinks : [
                {
                    'text' : 'Characters',
                    'url' : '#'
                },
                {
                    'text' : 'Comics',
                    'url' : '#'
                },
                {
                    'text' : 'Movies',
                    'url' : '#'
                },
                {
                    'text' : 'TV',
                    'url' : '#'
                },
                {
                    'text' : 'Games',
                    'url' : '#'
                },
                {
                    'text' : 'Videos',
                    'url' : '#'
                },
                {
                    'text' : 'News',
                    'url' : '#'
                },
                
            ],

            dcShopsLinks : [
                {
                    'text' : 'Shop DC',
                    'url' : '#'
                },
                {
                    'text' : 'Shop DC Collectibles',
                    'url' : '#'
                }
            ],

            dcLinks : [
                {
                    'text' : 'Terms of Use',
                    'url' : '#'
                },
                {
                    'text' : 'Privacy Policy (New)',
                    'url' : '#'
                },
                {
                    'text' : 'Ad Choices',
                    'url' : '#'
                },
                {
                    'text' : 'Advertising',
                    'url' : '#'
                },
                {
                    'text' : 'Jobs',
                    'url' : '#'
                },
                {
                    'text' : 'Subscriptions',
                    'url' : '#'
                },
                {
                    'text' : 'Talent Workshop',
                    'url' : '#'
                },
                {
                    'text' : 'CPSC Certificates',
                    'url' : '#'
                },
                {
                    'text' : 'Ratings',
                    'url' : '#'
                },
                {
                    'text' : 'Shop Help',
                    'url' : '#'
                },
                {
                    'text' : 'Contact Us',
                    'url' : '#'
                }
            ],

            dcSitesLinks : [
                {
                    'text' : 'DC',
                    'url' : '#'
                },
                {
                    'text' : 'MAD Magazine',
                    'url' : '#'
                },
                {
                    'text' : 'DC Kids',
                    'url' : '#'
                },
                {
                    'text' : 'DC Universe',
                    'url' : '#'
                },
                {
                    'text' : 'DC Power Vise',
                    'url' : '#'
                },                
            ],

        }
    }

}
</script>

<style lang="scss" scoped>

footer {
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;
    color: white;
    font-size: 0.75rem;
}

.background-logo {
    // TODO: Create mixins
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

a {
    text-decoration: none;
    color: grey;
}

</style>