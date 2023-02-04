<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <SidebarMenu />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import DashboardComponent from "./components/Dashboard.vue";
import SidebarMenu from "./components/SidebarMenu.vue";

export default {
  name: "App",
  components: {
    // DashboardComponent,
    SidebarMenu
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
