<template>
  <div id="app">
    <Counter :year="2025" :month="4" :date="29" :hour="0" :minute="0" :second="0" :millisecond="0" />
  </div>
</template>

<script>
import Counter from "@/components/Counter.vue";
export default {
  name: "App",
  components: {
    Counter
  }
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
