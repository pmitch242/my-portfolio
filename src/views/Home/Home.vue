<template>
  <div class="home">
    <Hero />
    <Services />
    <Offer />
    <Portfolio />
    <About />
    <Contact />
  </div>
</template>

<script>
import Hero from "./Hero";
import Services from "./Services";
import Offer from "./Offer";
import Portfolio from "./Portfolio";
import About from "./About";
import Contact from "./Contact";

export default {
  name: "Home",
  components: {
    Hero,
    Services,
    Offer,
    Portfolio,
    About,
    Contact
  }
};
</script>
