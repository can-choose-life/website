<template>

<div id="banner">
  <img src="/home.jpg" id="banner-image" />
  <div id="banner-title-container"> 
    <h1 class="banner-text"> Обирай Життя </h1>
    <p class="awsm-font banner-text"> Християнський центр ресоціалізації </p>
  </div>
</div>

</template>

<style>

@import url('https://fonts.googleapis.com/css?family=Young+Serif&display=swap');
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');

.awsm-font {
  font-family: "Montserrat";
}

.awsm-font2 {
  font-family: "Young Serif";
}

.theme-default-content {
  max-width: none !important;
  padding: 0 !important;
}
/*
.theme-default-content > * {
  margin-top: 50px !important;
}
*/
.theme-default-content > #banner + .banner-text {
  margin-top: -50px !important;
}

.navbar {
  position: absolute !important;
  background-color: transparent !important;
  border-bottom: none !important;
}

.logo {
  margin-right: 0px !important;
}

.page {
  padding-bottom: 0 !important;
}

.links {
  background-color: transparent !important;
}

#banner {
  width: 100%;
  heigth: 700px;
  transform: translateY(-60px);
}

#banner-image {
  width: 100%;
  opacity: 0.4;
}

#banner-title-container {
  margin: 0 auto;
  width: 400px;
  height: 1px;
}

#banner-title-container > p {
  font-size: 0.9em;
}

#banner-title-container {
  transform: translateY(-130px) scale(1.3);
}

@media screen and (min-width: 480px) {
  #banner-title-container {
    transform: translateY(-200px) scale(1.4);
  }
}

@media screen and (min-width: 720px) {
  #banner-title-container {
    transform: translateY(-300px) scale(2);
  }
}

@media screen and (min-width: 900px) {
  #banner-title-container {
    transform: translateY(-400px) scale(2);
  }
}

@media screen and (min-width: 1050px) {
  #banner-title-container {
    transform: translateY(-500px) scale(2);
  }
}


.banner-text {
  text-align: center;
}

h1.banner-text {
  font-family: "Young Serif";
  color: inherit;
}

</style>
