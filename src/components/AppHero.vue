<script>
export default {
  data() {
    return {
      jumbotronFiller: "Jumbotron",
    };
  },
};
</script>

<template>
  <div class="container">
    <div class="jumbotron">
      <h1>{{ jumbotronFiller }}</h1>
      <img src="../assets/vue.svg" alt="" />
    </div>
  </div>
</template>

<style lang="scss">
.container {
  width: 80%;
  margin: auto;
  .jumbotron {
    background-color: rgba(195, 186, 186, 0.975);
    text-align: center;
    height: 500px;
    h1 {
      padding: 2rem;
    }
    img {
      height: 200px;
    }
  }
}
</style>
