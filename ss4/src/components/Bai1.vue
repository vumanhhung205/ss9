<template>
  <div>
    <h1>bài 1</h1>
    Email: <input type="text" v-model="email">
    <p>giá trị :{{ email }}</p>
    
  </div>
</template>

<script setup>
import {ref} from 'vue';
const email = ref("")

</script>

<style>

</style>