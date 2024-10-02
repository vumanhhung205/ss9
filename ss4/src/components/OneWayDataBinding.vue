<template>
<div>
    <h1>One Way Data Binding</h1>
    <h3>Username :{{ userName }}</h3>
    <input type="text" :value ="userName">
    <button @click="handleChangeName">Change Name</button>
</div>

</template> 
<script setup>
    import {ref} from 'vue';
    const userName = ref ("nguyen van B");
    const handleChangeName = () => {
        userName.value="nguyen van A"
    };

</script>