<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <img src="@/assets/img/dc-logo.png" alt="">
            </div>
            <div class="col">
                <ul class="navbar">
                    <li v-for="(link, index) in links" :key=index><a :href="link.url">{{link.text}}</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Header",
    data (){
        return {
            links: [
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
  {
    text: 'Shop',
    url: '#',
    current: false,
  },
],

        }

    }

}
</script>

<style lang="scss">

    .container {
        max-width: 1400px;
        font-size: 12px;
        font-family: 'Oswald', sans-serif;
    }
    .row {
        display: flex;
        justify-content: space-between;
    }
    .navbar li {
        display: inline;
        padding: 10px;
    }
    .navbar li a {
        text-decoration: none;
        color: #000;
    }
    ul .active {
        border-bottom: 1px solid #0282f9;
    }
    .active a {
        color: #0282f9;
    }
</style>