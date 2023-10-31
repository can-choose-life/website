<template>

<div id="about-us">
  <img src="/back-our-work.jpg" />
  <hr>
  <h1 class="awsm-font" >Наше служіння</h1>
  <Inform src="/ministry-1.jpg" title="Звістка Євангелії" text="Наша ціль звістити Божу вістку спасіння у Ісусі Христі." />
  <Inform src="/ministry-2.jpg" title="Допомога залежним" text="Допомога алко-, нарко- залежним та людям з іншими залежностями." />
  <Inform src="/ministry-3.jpg" title="Консультація рідних" text="Маємо зв'язок з рідними та близькими залежних." />
  <Inform src="/ministry-4.jpg" title="Дім милосердя" text="Допомога літнім людям, які потрапили в складні життеві ситуації." />
</div>

</template>

<style>

#about-us {
  width: 100%;
  background-color: #712528;
  overflow: clip;
}

#about-us > img {
  position: absolute;
  width: 100%;
  height: 1500px;
  opacity: 0.1;
  object-fit: cover;
}

#about-us > h1 {
  text-align: center;
  color: white;
  margin-left: 0;
}

#about-us > div {
  z-index: 1;
}

@media screen and (min-width: 720px) {
  #about-us > div {
    margin-left: 100px;
    margin-right: 100px;
  }
  #about-us > img {
    height: 1100px;
  }
}

</style>
