<template>
  <section>
    <div class="top-bar flex flex-row items-center justify-between w-100">
      <logo></logo>
    </div>
    <div class="middle-bar">Middle</div>
    <div class="w-50">
      <img class="img img-responsive" src alt>
    </div>
  </section>
</template>

<script>
import Logo from "~/components/Logo";

export default {
  name: "Hero",
  components: {
    Logo
  },
  methods: {}
};
</script>

<style>
</style>
