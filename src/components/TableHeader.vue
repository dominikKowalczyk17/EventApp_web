<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  columns: Array
});
</script>

<template>
  <tr>
    <th v-for="column in columns" :key="column" scope="col" class="px-4 py-4">
      {{ column }}
    </th>
  </tr>
</template>