<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <SidebarMenu />
    <h1><strong>Placeholder Header</strong></h1>
  <input type="url" name="url" id="userInput" placeholder="https://www.yelp.com/biz/your-business-here" size="100">

  <p>Enter your Yelp Business URL</p>
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
h1{
  text-align: center;
}

</style>
