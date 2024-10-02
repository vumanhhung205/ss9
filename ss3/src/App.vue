
<template>
<div>
   <img v-bind:scr="url" alt=""/>
   <!-- <img : scr="url" alt="" /> -->
 <button v-bind:disabled="isDisabled"></button>
 <input type="text" v-bind:disable="isEnter"/>
 <div v-bind="divAttributes">container</div>
</div>                    
<!-- Binding 2 thuộc tính i: "paragraph" , area="paragraph" -->
</template>

<script setup>
  const url =
 "https://blog.maika.ai/wp-content/uploads/2024/02/anh-meo-meme-8.jpg";
  const isDisabled = true ;

  const isEnter = true  ;
  const divAttributes ={
    id: "container-id",
    class: "container-class",
  };
</script>
<style></style>




 
