<script>
import Vue from "vue";
import VueCodesandbox from "@/vue-codesandbox.vue";

export default Vue.extend({
  name: "ServeDev",
  components: {
    VueCodesandbox,
  },
});
</script>

<template>
  <div id="app">
    <vue-codesandbox
      codeUrl="https://codesandbox.io/s/vue-vue?autoresize=1&fontsize=14&hidenavigation=1&theme=dark"
      width="1000"
      height="1000"
    />
  </div>
</template>
