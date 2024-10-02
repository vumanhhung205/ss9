<template>
    <div>
        <p>Giới tính : {{ gender }}</p>
              Nam <input v-model="gender" type="radio" value="nam" name="" id="">
              Nữ <input v-model="gender" type="radio" value="nữ" name="" id="">
              Khác <input v-model="gender" type="radio" value="khác" name="" id="">
    </div>
 
</template>

<script setup>
    import {ref} from 'vue';
    const gender = ref ('nam')

</script>

<style>

</style>