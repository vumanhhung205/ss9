<template>
  <div class="card">
    <div class="card-image">
      Image
    </div>
    <h3 class="card-title">Title</h3>
    <button class="card-button">Add to card</button>
  </div>
</template>

<script>
export default {
  name: "Card"
}
</script>

<style scoped>
.card {
  width: 200px;
  border: 1px solid #ccc;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  background-color: white;
  margin: 20px auto;
}

.card-image {
  background-color: gray;
  color: white;
  padding: 40px 0;
  font-size: 18px;
  border-bottom: 1px solid #ccc;
}

.card-title {
  font-size: 18px;
  margin: 15px 0;
}

.card-button {
  background-color: #f9f9f9;
  border: 1px solid #ccc;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  border-radius: 5px;
}

.card-button:hover {
  background-color: #eee;
}
</style>
