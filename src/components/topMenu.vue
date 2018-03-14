<template>
  <div class="top-menu">
    <div class="logo">
      <router-link tag="a" to="/main">
        <img src="../assets/img/logo.jpg" alt="Logo">
      </router-link>
    </div>
    <div class="menu">
      <router-link tag="a" to="/auth">Reg/Login</router-link>
    </div>
  </div>
</template>

<script>
</script>

<style lang="stylus" scoped>
@import '../assets/style/topMenu';
</style>
