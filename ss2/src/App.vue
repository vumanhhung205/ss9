<script setup>
import FooterComponent from "./components/FooterComponent.vue"
import Header from "./components/Header.vue"
import Menu from "./components/Menu.vue"
import User from "./components/User.vue"
import B1 from "./components/ListCourse.vue"
import B2 from "./components/ColorBox.vue"
import B3 from "./components/Card.vue"
import B4 from "./components/Calculation.vue"
import B5 from  "./components/UserInfo.vue"
import B6 from "./components/FormatName.vue"
import B7 from "./components/AdminIndex.vue"
</script>

<template>
<div>
  <h1>HelloWorld</h1>
  <Header></Header>
  <user />
  <Menu></Menu>
  <footer-component></footer-component>
  <B1 />
  <B2 />
  <B3 />
  <B4 />
  <B5 />
  <B6 />
  <B7 />
</div>
</template>