<script setup>
const API = 'https://cbu.uz/uz/arkhiv-kursov-valyut/json/'
fetch(API)
   .then(res => res.json())
   .then((data) => {
      console.log(data)
      let dollar = document.querySelector('.header-about_title')

      dollar.innerText = data[0].Rate
   })
   .catch(() => {
      console.log('xatolik bor')
   }) 
</script>

<template>
   <div class="container d-flex align-items-center">
      <div class="header-about w-50">
         <h1 class="header-about_title"></h1>
         <p></p>
      </div>
      <div class="header-image w-50"></div>
   </div>
</template>

<style scoped>

</style>