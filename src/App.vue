<script setup>
import { ref } from 'vue';


const count = ref(42);
</script>

<template>
  <div @click="count++" class="btn_cnt"> Count is {{ count }} </div>
  <button @click="count = 0"> Count Reset </button>
</template>

<style>
</style>