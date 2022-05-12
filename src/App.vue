<template>
  <div id="app">
    <app-header />
    <router-view />
  </div>
</template>
<script>

import AppHeader from "@/components/global/AppHeader.vue";

export default {
  name : 'App',
  components : {
    AppHeader,
  }
}
</script>
<style lang="scss">
@font-face {
  font-family: "Regular-Gravity";
  src: local("Regular-Gravity"),
   url(./fonts/gravity/Gravity-Regular.otf) format("truetype");
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
