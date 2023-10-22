<template>

<div id="home-social-networks">
<h2 class="awsm-font"> Ми в соціальних мережах </h2>
<img src="/phone.png" /> 
<img src="/laptop.png" />
</div>

</template>

<script>

window.addEventListener('load', () => {
  document.querySelector('#home-social-networks>img:nth-child(2)').onclick = () => document.location.href = 'https://instagram.com/obiraizhittia/' 
  document.querySelector('#home-social-networks>img:last-child').onclick   = () => document.location.href = 'https://www.facebook.com/profile.php?id=100092556792731' 
})


</script>

<style>

#home-social-networks {
  width: 100%;
  background-color: white;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  position: relative;
  padding-top: 0;
}

#home-social-networks > h2 {
  width: 100%;
  text-align: center;
  color: inherit !important;
}

#home-social-networks > img {
  width: 32%; /* phone with instagram */
  object-fit: contain;
  max-height: 500px;
  cursor: pointer;
  transition: transform 0.2s ease;
}

#home-social-networks > img:hover {
  transform: scale(1.05);
  transition: transform 0.2s ease;
}

#home-social-networks > img ~ img {
  width: 45%; /* laptop with facebook */
}

</style>
