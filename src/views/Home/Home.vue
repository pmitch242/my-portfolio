<template>
  <div class="home">
    <Hero />
    <Services />
    <Offer />
  </div>
</template>

<script>
import Hero from "./Hero";
import Services from "./Services";
import Offer from "./Offer";

export default {
  name: "Home",
  components: {
    Hero,
    Services,
    Offer
  }
};
</script>
