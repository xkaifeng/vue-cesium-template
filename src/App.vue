<!--
 * @Author: xkf
 * @Date: 2021-06-03 17:46:28
 * @LastEditTime: 2021-06-04 09:34:46
 * @FilePath: \cesium-item\src\App.vue
-->
<template>
  <div id="app">
    <EarthIndex />
  </div>
</template>

<script>
import EarthIndex from "./components/EarthIndex.vue";
export default {
  name: "App",
  components: {
    EarthIndex,
  },
};
</script>

<style lang="scss">
body,
html,
#app {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
}
</style>
