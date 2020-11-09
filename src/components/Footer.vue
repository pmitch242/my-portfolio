<template>
  <div id="footer">
    <img src="../images/footer-bg.png" alt="footer-bg" />
    <div class="container">
      <div class="footer-span-container">
        <span id="logo">Phill<span class="">Mitchell</span></span>
        <span class="subtitle">
          Website designed and coded by me... I am me.
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
#footer img {
  position: absolute;
}

.footer-span-container {
  display: flex;
  flex-direction: column;
}
</style>
