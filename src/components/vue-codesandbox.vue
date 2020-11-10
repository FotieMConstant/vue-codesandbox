<template>
  <div class="codesandbox">
    <embed type="text/html" :src="codeUrl" :width="width" :height="height" />
  </div>
</template>

<script>
export default {
  name: "vue-codesandbox",
  props: {
    codeUrl: String,
    width: Number,
    height: Number,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
