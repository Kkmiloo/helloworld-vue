<template>
  <CounterOption />
  <CounterComposition />
</template>

<script lang="ts" setup>
import CounterComposition from './components/CounterComposition.vue';
import CounterOption from './components/CounterOption.vue';
import PostContainer from './components/PostContainer.vue';
</script>

<style>
body {
  background-color: darkgray;
}
</style>
