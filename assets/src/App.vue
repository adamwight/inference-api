<template>
  <top-bar />
  <tool-holder />
  <info-footer />
</template>

<script>
import InfoFooter from "./components/InfoFooter.vue";
import TopBar from "./components/TopBar.vue";
import ToolHolder from "./components/ToolHolder.vue";

export default {
  name: "App",
  components: {
    InfoFooter,
    ToolHolder,
    TopBar
  }
};
</script>

<style lang="scss">
@use 'assets/legacy.scss';

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
