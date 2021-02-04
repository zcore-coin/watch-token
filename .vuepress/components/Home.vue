<template>
  <b-row class="p-0 pt-4">
    <b-col lg="8" offset-lg="2">
      <b-jumbotron bg-variant="light" header-level="4">
        <template slot="header">
          WatchToken
        </template>
        <template slot="lead">
          {{ $site.title }}
        </template>
        <hr class="my-4">
        <p>Create a Widget for your BEP20 Token. Add your Token to DApp browsers or MetaMask.</p>
        <b-button size="lg" variant="success" class="mt-2 text-uppercase p-3" to="/create/">
          Create BEP20 Widget
        </b-button>
 
      </b-jumbotron>
    </b-col>
  </b-row>
</template>

<script>
  export default {
    name: 'Home',
  };
</script>
