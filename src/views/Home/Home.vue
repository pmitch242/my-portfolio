<template>
  <div class="home">
    <Hero />
    <Services />
    <h1>First Vue App</h1>
  </div>
</template>

<script>
import Hero from "./Hero";
import Services from "./Services";

export default {
  name: "Home",
  components: {
    Hero,
    Services
  }
};
</script>
