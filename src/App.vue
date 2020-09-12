<template>
  <div id="app">
    <div class="container">
      <h2>front end mentor</h2>
    </div>
    <div class="container">
      <b-row>
        <b-col>
          <card status="completed" imgurl="./assets/challenge1.jpg" />
        </b-col>
        <b-col>
          <card status="incomplete" imgurl="https://picsum.photos/600/300/?image=25" />
        </b-col>
        <b-col>
          <card />
        </b-col>
        <b-col>
          <card />
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
import card from "./cards";
export default {
  name: "App",
  components: {
    card,
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
