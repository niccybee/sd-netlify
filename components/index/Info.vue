<template>
  <section>
    <div class="flex items-start w-100 pattern-band">
      <div class="w5 h5 bg-gold br-100 flex items-center justify-end">
        <h2 class="f-headline tc w-100">Info</h2>
      </div>
    </div>
    <div class="mid-section w-100 h-100 ma2 flex flex-column items-center justify-start">
      <div class="w-80-ns w-80 pa4-l pa4-m pa2 h-90 bg-white br2 shadow-1 rellax3 black">
        <h3 class="f2">Our Dukkah</h3>
        <p class="f4 pl3 pr3 lh-copy">
          We love grazing food…And our sprinkle n Dash dukkah is the sort of food that you put on the table at the beginning of the evening and people just help themselves to.
          <br>
          <br>We also enjoy nibbles, dips and platters. Adding our Dukkah will simply look amazing, tasty and easy to enjoy with your friends and drinks of course!
          <br>
          <br>Our Dukkah is a Palestinian style spice blend made with toasted nuts, seeds and spices that is normally eaten with bread and oil or It can be sprinkled on salads & eggs, Encrust your meats with it or Use as a meat marinade to take your BBQ to the next level it is sure to be a crowd pleaser!
          <br>
          <br>The rich flavor of toasted nuts and spices is so delicious that you can easily see yourself putting it on everything!
          If you haven’t tried Dukkah yet, you need to. Period!
        </p>
        <img class="nested-img img" src="https://picsum.photos/1200/600" alt>
        <p
          class="f4 pl3 pr3"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae unde, repudiandae exercitationem quas, nisi perferendis, cum laboriosam est rerum sit sequi minus alias accusamus molestias. Quasi, eos? Nulla, amet recusandae?</p>
      </div>
    </div>
  </section>
</template>

<script>
import Rellax from "rellax";
export default {
  mounted() {
    var rellax3 = new Rellax(".rellax3", {
      speed: -0.05,
      wrapper: null
    });
  }
};
</script>

<style>
.vw-100 {
  width: 100vw;
}
</style>
