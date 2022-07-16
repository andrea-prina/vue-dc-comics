<template>
    <div class="action-bar">
        <div class="container">
            <div class="row p-5">
                <div class="col text-center"><img src="../assets/img/buy-comics-digital-comics.png" alt="">DIGITAL COMICS</div>
                <div class="col text-center"><img src="../assets/img/buy-comics-merchandise.png" alt="">DC MERCHANDISE</div>
                <div class="col text-center"><img src="../assets/img/buy-comics-subscriptions.png" alt="">SUBSCRIPTIONS</div>
                <div class="col text-center"><img src="../assets/img/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</div>
                <div class="col text-center"><img src="../assets/img/buy-dc-power-visa.svg" alt="">DC POWER VISA</div>
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

    .action-bar{
        background-color: $brand-color;
        color: #FFF;

        img {
            height: 3rem;
            margin-right: 0.5rem;
        }
    }

</style>