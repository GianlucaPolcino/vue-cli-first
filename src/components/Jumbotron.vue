<template>
  <div class="container">
      <img src="https://i.imgflip.com/1qrjof.jpg" alt="">
      <h2 class="red">wow</h2>
      <h2 class="green">such professional</h2>
      <h2 class="white">very position absolute</h2>

  </div>
</template>

<script>
export default {
    name: "Jumbotron",
}
</script>

<style scoped>
    .container{
        position: relative;
        width: 90%;
        margin: 0 auto;
    }

    .container img{
        width: 100%;
    }

    .container h2{
        font-size: 40px;
    }

    .red{
        position: absolute;
        top: 10%;
        left: 10%;
        color: red;
    }

    .green{
        position: absolute;
        top: 30%;
        right: 12%;
        color: green;
    }

    .white{
        position: absolute;
        bottom: 5%;
        left: 5%;
        color: white;
    }
</style>