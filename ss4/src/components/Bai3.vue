<template>
    <div>
        <h1>bài 3</h1>
        ngày sinh <input type="date" name="" id="" v-model ="date">
        <p>ngày sinh: {{ date }}</p>
    </div>
  
</template>

<script setup>
import {ref} from 'vue';
    const date = ref(0)
</script>

<style>

</style>