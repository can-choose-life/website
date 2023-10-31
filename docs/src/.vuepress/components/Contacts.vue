<template>

<form id="contact-form" action="https://fabform.io/f/g8HA-nM" method="post">
  <h2 class="awsm-font">Напишіть нам</h2>
  <p class="awsm-font">І ми зв'яжемося з вами найближчим часом</p>
  <label class='awsm-font' for="firstName">*Ваше ім'я</label>
  <input name="firstName" type="text" required>
  <label class='awsm-font'for="phone">Номер телефону</label>
  <input name="phone" type="tel">
  <label class='awsm-font'for="email">Email</label>
  <input name="email" type="email">
  <br>
  <br>
  <label class='awsm-font' for="text">Повідомлення</label>
  <textarea class='big-text' name="text" type="text" required></textarea>
  <br>
  <button class='awsm-font' type="submit">Надіслати</button>
</form>

</template>

<style>

#contact-form {
  margin: 20px;
}

@media screen and (min-width: 720px) {
  #contact-form {
    max-width: 1000px;
    margin: 0 auto;
  }
}

#contact-form > label, #contact-form > input, #contact-form > textarea, #contact-form > button {
  margin: 10px;
}

#contact-form > h2, #contact-form > p {
  color: inherit;
  text-align: center;
}


.big-text {
  width: 90%;
  height: 300px;
}

</style>
