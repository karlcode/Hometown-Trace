<template>
  <div class="hello">
    <div id="myMap"></div>
  </div>
</template>

<script>
export default {
  name: "MapView",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  },
  mounted: function() {
    console.log("map: ", google.maps);
    this.map = new google.maps.Map(document.getElementById("myMap"), {
      center: { lat: 0, lng: 0 },
      scrollwheel: true,
      zoom: 6
    });
  }
};
</script>
<style scoped>
#myMap {
  height: 500px;
  width: 100%;
}
</style>
