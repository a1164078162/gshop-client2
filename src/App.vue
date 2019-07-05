<template>
  <div id="app">
    <router-view></router-view>
    <FooterGuide></FooterGuide>
  </div>
</template>

<script type="text/ecmascript-6">
import FooterGuide from "./components/FooterGuide/FooterGuide.vue";
export default {
  // name: "App",
  // data() {
  //   return {
  //     msg: "App Component"
  //   };
  // },
  components: {
    FooterGuide
  }
};
</script>

<style lang="stylus" rel="stylesheet/stylus" scoped>
#app
  color red
</style>
