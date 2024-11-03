<script lang="ts" setup>

</script>

<template>
  <div>
    <h1>Home</h1>
    <RouterLink :to="{ name: '/projects/[id]', params: { 'id': '1' } }">Go to Projects 1</RouterLink>
  </div>
</template>
