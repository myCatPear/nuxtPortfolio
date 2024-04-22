<template>
  <NuxtLayout>
    <section>
      {{ error }}
      <h1 class="text-4xl mb-4">Oops {{ error.statusCode }}</h1>
      <h2>
        {{ error.statusMessage }}
      </h2>
    </section>
  </NuxtLayout>
</template>

<script setup>
defineProps({ error: Object });
</script>
