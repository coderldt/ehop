<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1024 1024">
    <path
      fill="currentColor"
      d="M256 768h672a32 32 0 1 1 0 64H224a32 32 0 0 1-32-32V96a32 32 0 0 1 64 0v672z"
    />
    <path
      fill="currentColor"
      d="M832 224v704a32 32 0 1 1-64 0V256H96a32 32 0 0 1 0-64h704a32 32 0 0 1 32 32z"
    />
  </svg>
</template>
<script lang="ts">
import type { DefineComponent } from 'vue'
export default {
  name: 'Crop',
} as DefineComponent
</script>
