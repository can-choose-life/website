<template>

<div class="flex-container">
  <div class="flex-item inform-text">
    <h2 class="awsm-font">{{ title }}</h2>
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

.inform-text > p, .inform-text > h2, .inform-text > h1 {
  color: white;
  text-align: center;
  border: none;
  margin-left: 5%;
  margin-right: 5%;
}

.inform-text > h2 {
  font-size: 1.9em;
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
  .inform-text > p, .inform-text > h2 {
    text-align: left;
    margin-left: 0;
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
