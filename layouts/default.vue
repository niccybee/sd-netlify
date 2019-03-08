<template>
  <div class="wrap">
    <nav-bar :class="displayNav ? navShow.showNav : navShow.hideNav"></nav-bar>
    <div class="base flex items-center justify-center flex-column tc">
      <nuxt/>
    </div>
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
        hideNav: "hidden",
        hideNav2: "bg-blue ba b--yellow orange"
      }
    };
  }
};
</script>
<style>
p,
a {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
    Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
h1,
h2,
h3 {
  font-family: "Arvo", "Karnak", "Calvert", "American Typewriter", Georgia,
    "Times New Roman", Times, serif;
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
/* Fix */
.hidden {
  display: none;
  visibility: hidden;
  color: blue;
}
</style>
