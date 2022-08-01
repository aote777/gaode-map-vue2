<template>
  <div class="about" id="map-container"></div>
</template>

<script>
export default {
  name: 'about',
  data() {
    return {}
  },
  mounted() {
    var map = new AMap.Map('map-container')
  },
  methods: {},
}
</script>

<style lang="scss">
.about {
  height: 800px;
}
</style>
