<template>
  <div>
    <h1>Thông tin cá nhân</h1>
    <h3><li>Họ và tên : {{ username }} </li></h3>
    <h3><li>Giới tính : {{ sex }} </li></h3>
    <h3><li>Ngày sinh : {{ birthday }} </li></h3>
    <h3><li>Email : {{ email }} </li></h3>
    <h3><li>Địa chỉ : {{ address }} </li></h3>
  </div>
</template>

<script>
const username ="Nguyen Van A";
const sex ="Nam";
const birthday ="06/03/2024";
const email ="nva@gmail.com";
const address ="Thanh Xuan , Ha Noi"

console.log("Họ và tên ", username)
console.log("Giới tính", sex)
console.log("Ngày sinh", birthday)
console.log("Email" , email)
console.log("Địa chỉ", address)
</script>

<style>

</style>