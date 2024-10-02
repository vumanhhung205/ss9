<template>
  <div>
    <p>Họ và tên: {{ formattedName }}</p>
  </div>
</template>

<script>
export default {
  name: 'FormatName',
  data() {
    return {
      user: {
        firstName: 'Nguyen van',
        lastName: 'nam'
      }
    };
  },
  computed: {
    formattedName() {
      return this.formatName(this.user);
    }
  },
  methods: {
    formatName(user) {
      const capitalize = (name) => {
        return name
          .toLowerCase()
          .replace(/\b\w/g, (char) => char.toUpperCase());
      };
      return `${capitalize(user.firstName)} ${capitalize(user.lastName)}`;
    }
  }
};
</script>

<style scoped>
/* Optional: Add some styling here */
</style>
