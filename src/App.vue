<script setup>
  import NavBar from './components/NavBar.vue'
  import UploadForm from './components/UploadForm.vue'
  import ImageGrid from './components/ImageGrid.vue'
</script>

<template>
  <NavBar />
  <UploadForm />
  <ImageGrid />
</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
