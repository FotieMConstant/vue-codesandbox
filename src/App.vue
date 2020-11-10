<template>
  <div id="app">
    <vuecodesandbox
      codeUrl="https://codesandbox.io/s/vue-vue?autoresize=1&fontsize=14&hidenavigation=1&theme=dark"
      width="1000"
      height="1000"
    />
  </div>
</template>

<script>
import vuecodesandbox from "./components/vue-codesandbox.vue";

export default {
  name: "App",
  components: {
    vuecodesandbox,
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
