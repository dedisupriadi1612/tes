<template>
  <v-app>
    <v-app-bar app>
      header
    </v-app-bar>

    <v-navigation-drawer app>
      side menu
    </v-navigation-drawer>

    <v-content>
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-content>

    <button onclick="/about">tes </button>

    <v-footer app>
      footer
    </v-footer>
  </v-app>
</template>
<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld 
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
