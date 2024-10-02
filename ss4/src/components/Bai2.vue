<template>
    <div>
        <h1>bài 2</h1>
        màu <input type="color" v-model="color">
        <p>mã màu: {{ color }}</p>
    </div>
  
</template>

<script setup>
import {ref} from 'vue';
const color = ref("")


</script>

<style>

</style>