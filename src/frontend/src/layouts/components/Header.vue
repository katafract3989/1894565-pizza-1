<template>
  <header class="header">
    <div class="header__logo">
      <router-link to="/" class="logo">
        <img
          src="@/assets/img/logo.svg"
          alt="V!U!E! Pizza logo"
          width="90"
          height="40"
        />
      </router-link>
    </div>
    <div class="header__cart">
      <router-link to="cart">{{ totalPrice }} ₽</router-link>
    </div>
    <div class="header__user">
      <router-link to="login" class="header__login"
        ><span>Войти</span></router-link
      >
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  props: {
    totalPrice: {
      type: Number,
      default: 0,
    },
  },
};
</script>

<style scoped></style>
