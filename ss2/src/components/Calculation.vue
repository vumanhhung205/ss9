<template>
  <div class="calculation">
    <h2>Danh sách kết quả</h2>
    <ul>
      <li>{{ a }} + {{ b }} = {{ add(a, b) }}</li>
      <li>{{ a }} - {{ b }} = {{ subtract(a, b) }}</li>
      <li>{{ a }} * {{ b }} = {{ multiply(a, b) }}</li>
      <li>{{ a }} / {{ b }} = {{ divide(a, b) }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      a: 10,
      b: 10 
    };
  },
  methods: {
    add(x, y) {
      return x + y;
    },
    subtract(x, y) {
      return x - y;
    },
    multiply(x, y) {
      return x * y;
    },
    divide(x, y) {
      if (y === 0) return "Không thể chia cho 0";
      return x / y;
    }
  }
};
</script>

<style scoped>
.calculation {
  font-family: Arial, sans-serif;
  margin: 20px;
}

h2 {
  font-size: 24px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  font-size: 18px;
  margin: 5px 0;
}
</style>
