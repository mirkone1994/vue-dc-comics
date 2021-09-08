<template>
  <div class="comics-card">
      <img :src="comic.thumb" :alt="comic.series">
      <h3>{{comic.series}}</h3>
  </div>
</template>

<script>
export default {
    name: "ComicsCard",
    props: ["comic"],

}
</script>

<style scoped lang="scss">
    .comics-card{
        flex-basis: calc(100% / 6);
        padding: 20px 0;
    }

</style>