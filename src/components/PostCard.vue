<template>
  <div class="post-card">
    <h3>title</h3>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe dolores
      nemo quia placeat ex suscipit hic ut labore rem nesciunt iste ullam et,
      perferendis tempora rerum excepturi dolorum delectus vitae?
    </p>
    <PostBtn />
  </div>
</template>

<script lang="ts" setup>
import PostBtn from './PostBtn.vue';
</script>

<style scoped>
.post-card {
  border-radius: 15px;

  padding: 10px;
  margin: 5px;
  border: 1px solid #ccc;
}
</style>
