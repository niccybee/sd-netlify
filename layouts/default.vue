<template>
  <div class="base flex items-center justify-center flex-column tc">
    <nav-bar :class="displayNav ? navShow.showNav : navShow.hideNav"></nav-bar>
    <nuxt/>
  </div>
</template>

<script>
// import tachyons from "tachyons";
import NavBar from "~/components/NavBar";

export default {
  components: {
    NavBar
  },
  data() {
    return {
      displayNav: false,
      navShow: {
        showNav: "black",
        hideNav: "bg-blue ba b--yellow orange"
      }
    };
  }
};
</script>
<style>
p {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
.base {
  background: black;
  color: white;
}
.bg-sd-green {
  background: linear-gradient(
      74.32deg,
      #3ea7ab -9.63%,
      rgba(255, 255, 255, 0) 85.94%
    ),
    #48babe;
}
</style>
