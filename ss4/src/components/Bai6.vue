<template>
    <div>
    <div>sở thích : {{ hobies }}</div>
    <div>
              <input value="đá bóng" v-model="hobies" type="checkbox" id=""> đá bóng
              <input value="bóng chuyền" v-model="hobies" type="checkbox" id=""> bóng chuyền
              <input value="code" v-model="hobies" type="checkbox" id=""> code
              <input value="bơi" v-model="hobies" type="checkbox" id=""> Bơi
          </div>
        </div>
  
</template>

<script setup>
import {ref} from 'vue';
const hobies = ref([])

</script>

<style>

</style>