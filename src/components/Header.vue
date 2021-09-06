<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <img src="@/assets/img/dc-logo.png" alt="">
            </div>
            <div class="col">
                <ul>
                    <li><a href="">CHARACTERS</a></li>
                    <li class="active"><a href="">COMICS</a></li>
                    <li><a href="">MOVIES</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">GAMES</a></li>
                    <li><a href="">COLLECTIBLES</a></li>
                    <li><a href="">VIDEOS</a></li>
                    <li><a href="">FANS</a></li>
                    <li><a href="">NEWS</a></li>
                    <li><a href="">SHOP</a></li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Header"

}
</script>

<style lang="scss">

    .container {
        max-width: 1400px;
        height: 200px;
        font-size: 12px;
        font-family: 'Oswald', sans-serif;
    }
    .row {
        display: flex;
        justify-content: space-between;
    }
    ul li {
        display: inline;
        padding: 10px;
    }
    ul li a {
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