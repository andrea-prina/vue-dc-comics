<template>

    <div class="social-bar">
        <div class="container d-flex justify-content-between">
            <a href="" class="btn">SIGN-UP NOW!</a>
            <div class="d-flex align-items-center">
                <h6 class="mb-0"><a href="">FOLLOW US</a></h6>
                <a class="ms-3" href=""><img src="../assets/img/footer-facebook.png" alt="facebook-logo"></a>
                <a class="ms-3" href=""><img src="../assets/img/footer-twitter.png" alt="twitter-logo"></a>
                <a class="ms-3" href=""><img src="../assets/img/footer-youtube.png" alt="youtube-logo"></a>
                <a class="ms-3" href=""><img src="../assets/img/footer-pinterest.png" alt="pinterest-logo"></a>
                <a class="ms-3" href=""><img src="../assets/img/footer-periscope.png" alt="periscope-logo"></a>
            </div>
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style lang="scss">
@import "../style/variables.scss";

    .social-bar {
        padding: 2rem 0;
        background-color: #303030;

        .btn {
            border: 1px solid $brand-color;
            color: white;
        }

        a {
            text-decoration: none;
            color: $brand-color;
            margin-bottom: 0;
            font-weight: bold;
        }
    }

</style>