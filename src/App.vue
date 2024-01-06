<!-- App.vue -->

<template>
  <div id="app">
    <h1>CKEditor Example Vue 3 Vite</h1>
		<div class="editor-wrapper"> 
        <ContentEditor/>
        </div> 
  </div>
</template>

<script setup>
import { ref } from 'vue'
import ContentEditor from './components/editors/ContentEditor.vue'
</script>

<style scoped>

</style>