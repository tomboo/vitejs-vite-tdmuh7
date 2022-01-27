<script setup>
  import { ref } from 'vue'

  const file = ref(null)

  function handleChange(e) {
    let selected = e.target.files[0]
    file.value = selected
    console.log(selected)
  }
</script>

<template>
  <h2>Upload Form</h2>
  <form>
    <label>
      <input type="file" @change="handleChange">
      <span>Upload Image</span>
    </label>
  </form>

  <div v-if="file">File: {{ file.name }}</div>
  <hr />
</template>

<style scoped>
</style>