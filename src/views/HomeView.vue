<script setup lang="ts">
import { useDragAndDrop } from '@formkit/drag-and-drop/vue'

const [parent, tapes] = useDragAndDrop([
  'Depeche Mode',
  'Duran Duran',
  'Pet Shop Boys',
  'Kraftwerk',
  'Tears for Fears',
  'Spandau Ballet'
])
</script>

<template>
  <main class="h-screen flex mx-auto w-full flex-col items-center">
    <h1 class="font-mono text-4xl mt-10 text-center">twenty øne piløts ranking songs</h1>
  </main>
</template>
