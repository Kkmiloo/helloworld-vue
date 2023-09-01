<template>
  <p
    :style="{
      backgroundColor: '#ccc',
      color: c,
    }"
  >
    El mensaje se ha enviado satisfactoriamente
  </p>

  <button @click="handleClick()">Color</button>
</template>

<script lang="ts" setup>
import { Ref, ref } from 'vue';
let c: Ref<string> = ref('#fff');
const handleClick = () => {
  c.value = '#222';
};
</script>

<style>
.danger {
  color: red;
}
</style>
