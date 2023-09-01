<template>
  <form action="">
    <input v-model="inputText" type="text" name="name" id="name" />
    <input type="checkbox" name="terms" id="terms" v-model="agree" /> acepto los
    terminos
  </form>

  <h3>{{ inputText }}</h3>
</template>

<script lang="ts" setup>
import { Ref, ref } from 'vue';

let inputText: Ref<string> = ref('');
let agree: Ref<boolean> = ref(true);
</script>

<style>
input {
  margin-top: 50px;
}
</style>
