<template>
  <CounterOption />
  <CounterComposition />
  <ExampleSelective />

  <ExampleFor />

  <ClassBind />
  <ModelForm />
</template>

<script lang="ts" setup>
import ClassBind from './components/ClassBind.vue';
import CounterComposition from './components/CounterComposition.vue';
import CounterOption from './components/CounterOption.vue';
import ExampleFor from './components/ExampleFor.vue';
import ExampleSelective from './components/ExampleSelective.vue';
import ModelForm from './components/ModelForm.vue';
import PostContainer from './components/PostContainer.vue';
</script>

<style>
body {
  background-color: darkgray;
}
</style>
