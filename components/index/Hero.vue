<template>
  <section>
    <div class="top-bar flex flex-row items-center justify-between w-100">
      <logo></logo>

      <nav class="ba b--yellow links w-40 flex flex-row white items-center justify-between pr4">
        <a class="link white" href="#about">About</a>
        <a class="link white" href="#shop">Shop</a>
        <a class="link white" href="#news">News</a>
      </nav>
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
