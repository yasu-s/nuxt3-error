<script setup lang="ts">
const error = useError()
</script>

<template>
  <div>
    <ul>
      <li>{{ error.statusCode }}</li>
      <li>{{ error.message }}</li>
    </ul>
  </div>
</template>