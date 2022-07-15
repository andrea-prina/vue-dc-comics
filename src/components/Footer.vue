<template>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-4 pt-4 pb-4">
                    <div class="container-fluid p-0">
                        <div class="row">
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                                <h6>SHOP</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                </ul>
                            </div>
                            <div class="col-4">
                                <h6>DC COMICS</h6>
                                <ul class="list-unstyled">
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
                                    <li>ITEM</li>
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

</style>