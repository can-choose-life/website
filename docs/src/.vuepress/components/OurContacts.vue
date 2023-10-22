<template>

<div class="two-flex-container">
  <div>
    <h2 class="awsm-font"> Наші контакти </h2>
    <p class="awsm-font"> Номер телефону: <b> +380969636242 </b> Томін Олексій </p>
    <p class="awsm-font"> Email: <b> life.choose2023@gmail.com </b> </p>
    <p class="awsm-font"> Адрес: <b> Україна, 62014, Харківська обл, Богодухівський р-н, село Пархомівка, вул Малиша Івана, будинок 99 </b> </p>
  </div>
  <SocialNetworks />
</div>

</template>

<style>

.two-flex-container {
  background-color: white;
  position: relative;
  padding-top: 20px;
}

.two-flex-container > div:first-child {
  border-right: 1px solid lightgray;
}

.two-flex-container > div {
  width: 100%;
}

@media screen and (min-width: 720px) {
  .two-flex-container {
    display: flex;
  }
  .two-flex-container > div {
    width: 50% !important;
  }
}

.two-flex-container h2 {
  color: inherit;
  text-align: center;
  border: none;
}

.two-flex-container p {
  text-align: left;
  margin-left: 10%;
}

.two-flex-container b {
  border: 1px solid gray;
  margin: 2px;
  padding: 2px;
}


</style>
