<template>
  <div>
    <Header />
    <div class="layout">
      <Menu />
      <Main />
    </div>
    <Footer />
  </div>
</template>

<script>
import header from './headerr.vue';
import menu from './menuu.vue';
import main from './mainn.vue';
import footer from './footerr.vue';

export default {
  components: {
    header,
    menu,
    main,
    footer
  }
}
</script>

<style scoped>
.layout {
  display: flex;
}

.layout > Menu {
  width: 200px;
}

.layout > Main {
  flex-grow: 1;
}

Header, Footer {
  background-color: #d3d3d3;
  padding: 10px;
  text-align: center;
}

Menu {
  background-color: #1f3b73;
  color: white;
  padding: 10px;
}

Main {
  padding: 10px;
  background-color: #f9f9f9;
}
</style>
