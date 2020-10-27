<template>
  <div class="container">
    <div id="cesiumContainer"></div>
  </div>
</template>

<script>
    import { Viewer } from 'cesium/Cesium'
    import  'cesium/Widgets/widgets.css'
    export default {
        name: "earth",
        data() {
            return {};
        },
        mounted() {
            let viewer = new Viewer("cesiumContainer");
        }
    };
</script>

<style scoped>
  .container {
    width: 100%;
    height: 100vh;
  }
  #cesiumContainer {
    width: 100%;
    height: 100vh;
  }
</style>
