<template>
 <section>
  <div class="flex items-start ba b--yellow w-100 pattern-band">
   <div class="w5 h5 bg-gold ba b--green br-100 flex items-center justify-end">
    <h2 class="f-headline tc w-100">About</h2>
   </div>

  </div>
  <div class="mid-section ba b--green w-100 h-100 ma2 flex flex-column items-center justify-start">
   <div class="w-90 h-90 bg-white br2 shadow-1 rellax2 black">
    <h3 class="f2"> Our Story</h3>
    <p class="f4 pl3 pr3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae unde, repudiandae exercitationem quas, nisi perferendis, cum laboriosam est rerum sit sequi minus alias accusamus molestias. Quasi, eos? Nulla, amet recusandae?</p>
    <img class="nested-img img" src="https://picsum.photos/1200/600" alt="">
    <p class="f4 pl3 pr3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae unde, repudiandae exercitationem quas, nisi perferendis, cum laboriosam est rerum sit sequi minus alias accusamus molestias. Quasi, eos? Nulla, amet recusandae?</p>
   </div>
  </div>
  <div class="bottom-section">bottom</div>
 </section>
</template>

<script>
import Rellax from "rellax";

export default {
  name: "About",
  mounted() {
    var rellax2 = new Rellax(".rellax2", {
      speed: -1,
      wrapper: null
    });
  },
  methods: {}
};
</script>

<style>
.pattern-band {
  background: url("~/assets/images/pattern.png");
}
</style>
