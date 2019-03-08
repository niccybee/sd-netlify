<template>
  <div class="logo ba b--yellow">
    <img id="logo" src="~/assets/images/logo-svg.svg" alt>
  </div>
</template>

<script>
export default {
  data() {
    return {
      inHeader: true
    };
  },
  mounted() {}
};
</script>


<style scoped>
.logo {
  height: 90%;
  margin: 2rem;
}
#logo {
  height: 40%;
}
</style>
