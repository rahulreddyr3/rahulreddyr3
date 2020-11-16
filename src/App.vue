<template>
  <html id="app">
    <index msg="Gojek"/>
  </html>
</template>

<script>
import index from "./components/index.vue";

export default {
  name: "App",
  components: {
    index,
  },
};
</script>

<style>
body, html{
  height: 100%;
  margin-bottom: 0;
  margin-left: 0;
  margin-top: 0;
  margin-right: 0;
}
</style>
