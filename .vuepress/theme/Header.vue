<template>
  <b-navbar toggleable="md" variant="light">
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

    <b-navbar-brand to="/">
      <b-img :src="$withBase('/assets/images/base-token.png')" height="24"/>
      WatchToken
    </b-navbar-brand>

    <b-collapse is-nav id="nav_collapse">
      <b-navbar-nav>


      </b-navbar-nav>
      <b-navbar-nav class="ml-auto">

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
  export default {
    name: 'Header',
  };
</script>
