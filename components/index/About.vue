<template>
  <section>
    <div class="flex items-start w-100 pattern-band">
      <div class="w5 h5 bg-gold br-100 flex items-center justify-end">
        <h2 class="f-headline tc w-100">About</h2>
      </div>
    </div>
    <div class="mid-section w-100 h-100 ma2 flex flex-column items-center justify-start">
      <div class="w-80-ns pa2 h-90 bg-white br2 shadow-1 rellax2 black">
        <h3 class="f2">Our Story</h3>
        <p
          class="f4 pl3 pr3 lh-copy"
        >This recipe was inspired by the heart of Palestine, Gaza. Two Melbourne friends have brought it back to life and to your home to be shared and enjoyed.
          <br>
          <br>A wonderful tangy, zesty, and salty blend of dry roasted Middle Eastern spices and seeds. Traditionally served for breakfast with bread dipped in olive oil. This delicious blend can be enjoyed as a snack or as part of a delicious recipe for lunch or dinner.
          <br>
          <br>Try using it as meat marinade or adding to roasted vegetables to take your meal to the next level. With a sprinkle and a dash of live oil the possibilities are endless
        </p>
        <img class="nested-img img" src="https://picsum.photos/1200/600" alt>
        <p
          class="f4 pl3 pr3"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae unde, repudiandae exercitationem quas, nisi perferendis, cum laboriosam est rerum sit sequi minus alias accusamus molestias. Quasi, eos? Nulla, amet recusandae?</p>
      </div>
    </div>
    <div class="bottom-section"></div>
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
