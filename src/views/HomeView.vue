<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import { ref } from 'vue'

const content = ref(`<div class='demo'>
    <p class='int'>hello Word</p>
</div>`)
</script>

<template>
  <main>
    <TheWelcome />
    <highlightjs autodetect :code="content" />
  </main>
</template>
