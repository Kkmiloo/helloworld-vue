<template>
  <div class="post-container">
    <PostCard />
    <PostCard />
    <PostCard />
  </div>
</template>

<script lang="ts" setup>
import PostCard from './PostCard.vue';
</script>

<style>
.post-container {
  display: flex;
  width: 100%;
  flex-wrap: wrap;
}
</style>
