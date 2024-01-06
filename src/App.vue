<!-- App.vue -->

<template>
  <div id="app">
    <h1>PMC Wagner Group</h1>
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