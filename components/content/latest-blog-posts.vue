<template>
  <BlogPosts v-slot="{ posts }">
    <div v-for="post in posts"></div>
  </BlogPosts>
</template>
