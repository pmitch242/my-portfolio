<template>
  <div id="nav">
    <div class="container">
      <b-navbar>
        <template slot="brand" class="primary">
          <b-navbar-item>
            <span class="logo">Phill<span>Mitchell</span></span>
          </b-navbar-item>
        </template>

        <!-- These links will colapes -->
        <template slot="end">
          <b-navbar-item>
            home
          </b-navbar-item>
          <b-navbar-item>
            portfolio
          </b-navbar-item>
          <b-navbar-item>
            about
          </b-navbar-item>
          <b-navbar-item>
            contact
          </b-navbar-item>
        </template>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style>
#nav {
  position: sticky;
  top: 0;
  z-index: 10000;
}

.navbar {
  background-color: transparent;
}
</style>
