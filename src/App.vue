<template>
  <div class="wrapper">
    <Title />
    <Jumbotron />
    <Apology />
  </div>
</template>

<script>
import Title from "./components/Title.vue"
import Jumbotron from "./components/Jumbotron.vue"
import Apology from "./components/Apology.vue"

export default {
  name: 'App',
  components: {
    Title,
    Jumbotron,
    Apology,
  }
}
</script>

<style lang="scss">
  .wrapper{
    text-align: center;
  }
</style>
