<template>
  <div class="container">
    <slot />
  </div>
</template>

<script>
export default {
  name: "AppLayoutDefault",
};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 300px;
}
</style>
