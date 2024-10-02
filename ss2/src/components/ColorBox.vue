<template>
  <div class="container">
    <div class="square-container">
      <div :style="{ width: '200px', height: '200px', backgroundColor: color1 }"></div>
      <button @click="color1 = 'red'">Red</button>
    </div>
    <div class="square-container">
      <div :style="{ width: '200px', height: '200px', backgroundColor: color2 }"></div>
      <button @click="color2 = 'blue'">Blue</button>
    </div>

    <div class="square-container">
      <div :style="{ width: '200px', height: '200px', backgroundColor: color3 }"></div>
      <button @click="color3 = 'green'">Green</button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      color1: 'white',
      color2: 'white',
      color3: 'white',
    }
  }
}
</script>

<style scoped>
.container {
  display: flex;
  gap: 20px; 
}

.square-container {
  display: flex;
  flex-direction: column;
  align-items: center; 
}

button {
  margin-top: 10px;
}
</style>
