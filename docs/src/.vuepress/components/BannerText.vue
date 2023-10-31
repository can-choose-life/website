<template>

<div class="banner-text">
  <h1 class="awsm-font"> {{ title  }} </h1>
  <p class="awsm-font"> {{ text }} </p>
</div>

</template>

<script>

export default {
  props: ['title', 'text']
}

</script>

<style>

.banner-text {
  margin: 0 auto;
}

.banner-text > h1, .banner-text > p {
  text-align: center;
  color: inherit;
  margin-left: 0;
}

.banner-text > p {
  margin-left: 30px;
  margin-right: 30px;
}

@media screen and (min-width: 720px) {
  .banner-text > p {
    margin-left: 100px;
    margin-right: 100px;
  }
}

</style>
