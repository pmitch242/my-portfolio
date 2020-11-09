<template>
  <div id="about">
    <img
      class="about-bg-img"
      src="../../images/background-rec.png"
      alt="rec-bg"
    />
    <div class="container">
      <div class="columns">
        <div class="column is-half">
          <h4 class="">Hi, I'm</h4>
          <h3 class="">Phill Mitchell-Matsuyama</h3>
          <h6 class="">( they/them )</h6>
        </div>
      </div>
      <div class="columns">
        <div class="column one-third">
          <img src="../../images/me.png" alt="Phill" />
        </div>
        <div class="column">
          <p class="">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
            erat, sed diam voluptua. At vero
          </p>
          <p class="">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam
            erat, sed diam voluptua. At vero eos et accusam et justo duo dolores
            et ea rebum. Stet clita kasd.
          </p>
          <button class="button is-primary">Primary</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About"
};
</script>

<style>
#about {
  background-color: #ffffff;
}

.about-bg-img {
  position: absolute;
  width: 65%;
  /* top: -22%; */
  right: -40%;
}
</style>
