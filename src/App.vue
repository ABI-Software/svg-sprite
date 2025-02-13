<script setup name="App">
import MapSvgSpriteColor from './components/SvgSpriteColor.vue'
import MapSvgIcon from './components/SvgIcon.vue'

console.log(MapSvgSpriteColor);
console.log(MapSvgIcon);
</script>

<template>
  <div id="app">
    <MapSvgSpriteColor />
    <div>
      Image
    </div>
    <img alt="Vue logo" src="@/../assets/logo.png">
    <div>
      SVG Icons
    </div>
    magnifyingGlass<MapSvgIcon icon="magnifyingGlass" class="example-icon" />
    changeBckgd<MapSvgIcon icon="changeBckgd" class="example-icon" />
    close<MapSvgIcon icon="close" class="example-icon" />
    closeFullScreen<MapSvgIcon icon="closeFullScreen" class="example-icon" />
    dock<MapSvgIcon icon="dock" class="example-icon" />
    pause<MapSvgIcon icon="pause" class="example-icon" />
    permalink<MapSvgIcon icon="permalink" class="example-icon" />
    play<MapSvgIcon icon="play" class="example-icon" />
    resetZoom<MapSvgIcon icon="resetZoom" class="example-icon" />
    tooltips<MapSvgIcon icon="tooltips" class="example-icon" />
    undock<MapSvgIcon icon="undock" class="example-icon" />
    zoomIn<MapSvgIcon icon="zoomIn" class="example-icon" />
    zoomOut<MapSvgIcon icon="zoomOut" class="example-icon"/>
    singlepanel<MapSvgIcon icon="singlepanel" class="example-icon" />
    2horpanel<MapSvgIcon icon="2horpanel" class="example-icon" />
    2vertpanel<MapSvgIcon icon="2vertpanel" class="example-icon" />
    3panel<MapSvgIcon icon="3panel" class="example-icon" />
    4panel<MapSvgIcon icon="4panel" class="example-icon" />
    fitWindow<MapSvgIcon icon="fitWindow" class="example-icon" />
    Help<MapSvgIcon icon="help" class="example-icon"/>
    openMap<MapSvgIcon icon="openMap" class="example-icon" />
    drawLine<MapSvgIcon icon="drawLine" class="example-icon" />
    drawPolygon<MapSvgIcon icon="drawPolygon" class="example-icon" />
    drawPoint<MapSvgIcon icon="drawPoint" class="example-icon" />
    drawTrash<MapSvgIcon icon="drawTrash" class="example-icon" />
    connection<MapSvgIcon icon="connection" class="example-icon" />
    comment<MapSvgIcon icon="comment" class="example-icon" />
    globalSetting<MapSvgIcon icon="globalSetting" class="example-icon" />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.example-icon{
  font-size: 30em;
}

.map-icon {
  color: red;
}

</style>
