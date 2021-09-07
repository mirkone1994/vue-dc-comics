<template>
<div class="section">
    <div class="container">
        <div class="row">
            <div class="col">
                <span class="sign-up">SIGN-UP NOW</span>
            </div>
            <div class="col">
                <div class="container">
                    <div class="row">
                        <div class="col">
                        <span class="follow">FOLLOW US</span>
                        </div>
                        <div class="col">
                            <img src="@/assets/img/footer-facebook.png" alt="">
                        </div>
                        <div class="col">
                            <img src="@/assets/img/footer-twitter.png" alt="">
                        </div>
                        <div class="col">
                            <img src="@/assets/img/footer-youtube.png" alt="">
                        </div>
                        <div class="col">
                            <img src="@/assets/img/footer-pinterest.png" alt="">
                        </div>
                        <div class="col">
                            <img src="@/assets/img/footer-periscope.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: "Footer"

}
</script>

<style scoped lang="scss">
    .section {
        background-color: #303030;
        height: 150px;
    }
    .container {
        max-width: 1400px;
        height: 100%;
    }
    .row {
        display: flex;
        height: 100%;
        justify-content: space-between;
    }
    .sign-up {
        color: #fff;
        border: 1px solid #0282f9;
        padding: 5px 10px;
    }
    .follow {
        color: #0282f9;
        font-size: 1.5em;
    }

</style>