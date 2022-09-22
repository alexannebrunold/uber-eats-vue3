<template>
  <div id="app">
    <RestaurantRow />
  </div>
</template>

<script>
import RestaurantRow from './components/RestaurantRow.vue'

export default {
  name: "App",
  components: {
    RestaurantRow
  },
};
</script>

<style>
@import url("../src/assets/style/reset.css");
@import url("https://fonts.googleapis.com/css2?family=Roboto%3Awght%40300%3B400%3B700&display=swap");
#app {
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
