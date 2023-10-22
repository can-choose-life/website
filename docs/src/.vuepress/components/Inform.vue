<template>

<div class="flex-container">
  <div class="flex-item inform-text">
    <h1 class="awsm-font">{{ title }}</h1>
    <p class="awsm-font">{{ text }}</p>
  </div>
  <div class="flex-item">
    <img class="img" v-bind:src="src"/>
  </div>
</div>

</template>

<script>

export default {
  props: ['title', 'text', 'src']
}

</script>

<style>

.flex-container {
  display: flex;
  flex-direction: column-reverse;
  justify-content: center;
  margin: 0 auto;
  position: relative;
}

.flex-item {
  margin: 0 auto;
}

.inform-text > p, h1 {
  color: white;
  text-align: center;
  margin-left: 5%;
  margin-right: 5%;
}

@media screen and (min-width: 720px) {
  .flex-item {
    margin: 15px;
  }
  .flex-container {
    flex-direction: row-reverse;
    justify-content: flex-end;
    margin: 0 auto;
  }
  .inform-text > p, h1 {
    text-align: left;
    margin-right: 0;
  }
}

.img {
  height: 200px;
  width: 350px;
  object-fit: cover;
  border-radius: 20px;
  box-shadow: 0 0 10px 1px black;
}

</style>
