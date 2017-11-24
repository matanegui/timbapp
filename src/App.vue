<template>
  <v-app id="app" light>
    <toolbar> </toolbar>
    <main>
      <router-view></router-view>
    </main>
  </v-app>
</template>

<script>
import Toolbar from './components/Toolbar';

export default {
  name: 'app',
  components: {
    toolbar: Toolbar
  }
};
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

main {
  text-align: center;
  margin-top: 40px;
}

</style>
