<template>
  <div class="home">
    <Hero />
    <Services />
    <Offer />
    <Portfolio />
    <About />
  </div>
</template>

<script>
import Hero from "./Hero";
import Services from "./Services";
import Offer from "./Offer";
import Portfolio from "./Portfolio";
import About from "./About";

export default {
  name: "Home",
  components: {
    Hero,
    Services,
    Offer,
    Portfolio,
    About
  }
};
</script>
