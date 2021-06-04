<!--
 * @Author: xkf
 * @Date: 2021-06-03 17:46:28
 * @LastEditTime: 2021-06-04 09:50:58
 * @FilePath: \cesium-item\src\components\EarthIndex.vue
-->
<template>
  <div id="container"></div>
</template>

<script>
import { Viewer } from "cesium";
import "cesium/Build/Cesium/Widgets/widgets.css";
import "../assets/js/index.js";
export default {
  name: "EarthIndex",
  data() {
    return {};
  },
  mounted() {
    this.initViewer();
  },
  methods: {
    initViewer() {
      const viewer = new Viewer("container");
    },
  },
};
</script>

<style scoped lang="scss">
#container {
  width: 100%;
  height: 100%;
}
</style>
