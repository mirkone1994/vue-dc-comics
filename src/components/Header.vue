<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <img src="@/assets/img/dc-logo.png" alt="">
            </div>
            <div class="col"></div>
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
        max-width: 1200px;
        height: 200px;
    }
    .row {
        display: flex;
        justify-content: space-between;
    }
</style>