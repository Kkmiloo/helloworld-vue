<template>
  <h1 v-if="age > 18">Eres mayor de edad</h1>
  <h1 v-else>Eres menor de edad</h1>
</template>

<script lang="ts" setup>
let age = 20;
</script>

<style scoped></style>
