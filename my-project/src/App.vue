<template>
  <div id="app">
    <Top></Top>
    <img src="./assets/logo.png">
    <router-view/>
    <Bottom></Bottom>
  </div>
</template>

<script>
import Top from "./components/Header";
import Bottom from "./components/Footer"
export default {
  name: "app",
  components: {
    Top,
    Bottom
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
