<template>
  <div class="popup">
    <router-link to="/card" class="close">
      <span class="visually-hidden">Закрыть попап</span>
    </router-link>
    <div class="popup__title">
      <h2 class="title">Спасибо за заказ</h2>
    </div>
    <p>Мы начали готовить Ваш заказ, скоро привезём его вам ;)</p>
    <div class="popup__button">
      <router-link to="/order" class="button">Отлично, я жду!</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "ThanksOrder",
};
</script>
