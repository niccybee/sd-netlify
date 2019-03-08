<template>
  <main class="wrap flex flex-column items-center justify-center w-100 ns-w-80">
    <hero
      class="rellax bg-sd-green ma3 w-90 vh-90 br2 pa1 flex items-center justify-between flex-column"
    ></hero>
    <about class="w-100 pa3 flex items-center justify-between flex-column"></about>
    <info class="w-100 pa3 flex items-center justify-between flex-column vh-90"></info>
  </main>
</template>

<script>
import Hero from "~/components/index/Hero.vue";
import About from "~/components/index/about.vue";
import Info from "~/components/index/info.vue";
import Logo from "~/components/Logo.vue";
import Rellax from "rellax";

export default {
  components: {
    Hero,
    About,
    Info,
    Logo
  },
  mounted() {
    var rellax = new Rellax(".rellax", {
      speed: 2,
      wrapper: null
    });
  }
};
</script>

<style>
.vh-90 {
  height: 90vh;
}
.w-90 {
  width: 90%;
}
</style>
