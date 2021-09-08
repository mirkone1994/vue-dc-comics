<template>
<div class="section">
    <div class="container">
      <div class="row">
          <div v-for="(link, index) in links" :key="index" class="col">
              <img :src="link.image" :alt="link.text">
              <span>{{link.text}}</span>
          </div>
      </div>
  </div>
</div>
  
</template>

<script>
export default {
    name: "Links",
    data() {
        return {
            links: [
                {
                    image: require("../assets/img/buy-comics-digital-comics.png"),
                    text: "DIGITAL COMICS",
                },
                {
                    image: require("../assets/img/buy-comics-shop-locator.png"),
                    text: "DC MERCHANDISE",
                },
                {
                    image: require("../assets/img/buy-comics-subscriptions.png"),
                    text: "SUBSCRIPTION",
                },
                {
                    image: require("../assets/img/buy-comics-digital-comics.png"),
                    text: "COMIC SHOP LOCATOR",
                },
                {
                    image: require("../assets/img/buy-dc-power-visa.svg"),
                    text: "DC POWER VISA",
                }
            ]
        }
    }

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