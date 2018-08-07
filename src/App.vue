<template>
  <div id="app">
    <h1>Gallery</h1>
    <Gallery />
  </div>
</template>

<script>
import Gallery from './components/Gallery.vue';

export default {
  name: "app",
  components: {
    Gallery
  }
};
</script>

<style lang="scss">
#app {
  h1 {
    text-transform: uppercase;
    color: silver;
    font-size: 4rem;
    letter-spacing: 40px;
  }

  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
