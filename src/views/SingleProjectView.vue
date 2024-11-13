<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
const projectId = route.params?.id

console.log(projectId)
</script>
<template>
  <div>
    <h1>Project {{ projectId }} Page</h1>
    <RouterLink to="/">Home Page</RouterLink>
  </div>
</template>
<style scoped></style>
