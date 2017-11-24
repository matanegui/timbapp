<template>
  <v-toolbar color="primary">
    <img src="../assets/logo.svg" class="title-icon">
    <v-toolbar-title class="app-title">{{title}}</v-toolbar-title>
    <v-btn color="secondary" medium absolute bottom right fab>
        <v-icon>add</v-icon>
    </v-btn>
  </v-toolbar>
</template>

<script>
  export default {
    name: 'toolbar',
    data() {
      return {
        title: 'Test'
      };
    }
  };
</script>

<style>
  .app-title {
    font-size: 2.2em;
    font-weight: light;
  }

  .title-icon {
    width: 2.5em;
    height: 2.5em;
  }
</style>
