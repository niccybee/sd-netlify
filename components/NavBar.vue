<template>
  <header class="fixed z-5 w-100 h3 flex flex-row justify-between items-center">
    <div class="pl4">
      <logo></logo>
    </div>
    <nav class="links w-40 flex flex-row white items-center justify-between pr4">
      <a class="link white" href="#about">About</a>
      <a class="link white" href="#shop">Shop</a>
      <a class="link white" href="#news">News</a>
    </nav>
  </header>
</template>

<script>
import Logo from "~/components/Logo";

export default {
  name: "NavBar",
  components: {
    Logo
  },
  data() {
    showBar: false;
  }
};
</script>

<style scoped>
</style>
