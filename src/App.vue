<template>
  <CounterOption />
  <CounterComposition />
  <ExampleSelective />

  <ExampleFor />

  <ClassBind />
</template>

<script lang="ts" setup>
import ClassBind from './components/ClassBind.vue';
import CounterComposition from './components/CounterComposition.vue';
import CounterOption from './components/CounterOption.vue';
import ExampleFor from './components/ExampleFor.vue';
import ExampleSelective from './components/ExampleSelective.vue';
import PostContainer from './components/PostContainer.vue';
</script>

<style>
body {
  background-color: darkgray;
}
</style>
