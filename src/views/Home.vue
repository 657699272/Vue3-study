<template>
  <div class="home">
    {{ name }}
  </div>
</template>

<script setup>
import { ref } from 'vue';
const name = ref('shen');
</script>
