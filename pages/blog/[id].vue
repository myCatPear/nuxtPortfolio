<template>
  We are inside a blog
  <div>Blog id is {{ route.params.id }}</div>
</template>

<script setup lang="ts">
const route = useRoute();

console.log(route);
</script>
