<template>
  <ul>
    <li v-for="country in countries" v-bind:key="country.code">
      {{ country.name }}
    </li>
  </ul>
</template>
<script lang="ts" setup>
import { Ref, ref } from 'vue';

interface ICountry {
  code: string;
  name: string;
}

let countries: Ref<Array<ICountry>> = ref([
  { code: 'ese', name: 'spain' },
  { code: 'UK', name: 'Unidet Kindom' },
  { code: 'FR', name: 'francia' },
  { code: 'CO', name: 'colombia' },
]);
</script>

<style scoped></style>
