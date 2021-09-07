<template>
<div class="section">
    <div class="container">
      <div class="row">
          <div class="col">
              <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
              <span>DIGITAL COMICS</span>
          </div>
          <div class="col">
              <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
              <span>DC MERCHANDISE</span>
          </div>
          <div class="col">
              <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
              <span>SUBSCRIPTION</span>
          </div>
          <div class="col">
              <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
              <span>COMIC SHOP LOCATOR</span>
          </div>
          <div class="col">
              <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
              <span>DC POWER VISA</span>
          </div>
      </div>
  </div>
</div>
  
</template>

<script>
export default {
    name: "Links",

}
</script>

<style scoped lang="scss">
    .section {
        background-color: #0282f9;
        position: relative;
        z-index: 2;
    }
    .container {
        height: 200px;
    }
    .row {
        justify-content: space-around;
        height: 100%;
    }
    .col {
        display: flex;
        align-items: center;
    }
    img {
        height: 50px;
    }
    span {
        vertical-align: center;
        color: #fff;
        padding-left: 10px;
    }

</style>