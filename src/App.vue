<script setup>
import { RouterView } from 'vue-router'

defineProps({
  navHome: {
    default: false,
    type: Boolean
  }
})
</script>

<template>
  <RouterView />
</template>
