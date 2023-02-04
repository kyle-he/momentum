<template>
  <div class="app">
    <div class="sidebar">
      <h3>Sidebar</h3>
      <p>Navigation menu goes here</p>
    </div>
    <div class="main-content">
      <h3>Main Content</h3>
      <p>Your main content goes here</p>
    </div>
  </div>
</template>

<style>
  .app {
    height: 100vh;
    display: flex;
  }
  
  .sidebar {
    width: 200px;
    height: 100%;
    background-color: lightgray;
    padding: 20px;
  }
  
  .main-content {
    flex: 1;
    padding: 20px;
  }
</style>

<script>
export default {
  name: "DashboardComponent"
};
</script>
