<template>
  <div id="app">
    <div class="container">
      <h2>Front End Mentor Challenges</h2>
    </div>
    <pageRoute />
  </div>
</template>

<script>
import pageRoute from "./pages/cardPage";
export default {
  name: "App",
  components: {
    pageRoute,
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
h2 {
  margin-bottom: 60px;
}
</style>
