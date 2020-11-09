<template>
  <div id="app">
    <div id="nav">
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
    <router-view />
  </div>
</template>

<script></script>
