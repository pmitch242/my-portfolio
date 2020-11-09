<template>
  <div class="home">
    <Hero />
    <h1>First Vue App</h1>
  </div>
</template>

<script>
import Hero from "./Hero";

export default {
  name: "Home",
  components: {
    Hero
  }
};
</script>
