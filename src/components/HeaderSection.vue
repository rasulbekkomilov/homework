<script setup>
// const API = 'https://cbu.uz/uz/arkhiv-kursov-valyut/json/'
// fetch(API)
//    .then(res => res.json())
//    .then((data) => {
//       console.log(data)
//       let dollar = document.querySelector('.header-about_title')

//       dollar.innerText = data[0].Rate
//    })
//    .catch(() => {
//       console.log('xatolik bor')
//    })
// FetchAPI sinaldi
</script>

<template>
   <div class="container d-flex align-items-center">
      <div class="header-about w-50">
         <h1 class="header-about_title text-lg-">Get Instant Loans</h1>
         <p class="header-about_paragraph">Get instant loans with ease on your smartphone.</p>
         <div class="d-flex w-75 image-container justify-content-between">
            <div class="google-icon w-50 img-fluid">
               <img class="google-icon w-75 img-fluid" src="@/assets/play-market-icon.png" alt="Play Market Icon">
            </div>
            <div class="appstore-icon w-50 img-fluid">
               <img class="appstore-icon w-75 img-fluid" src="@/assets/appstore-icon.png" alt="AppStore Icon">
            </div>
         </div>
      </div>
      <div class="header-image w-50">
         <img class="img-fluid" src="@/assets/header-img.png" alt="Header Image">
      </div>
   </div>
</template>

<style scoped>
@media (max-width: 700px) {
   .image-container{
      display: flex;
      /* flex-direction: column; */
   }
   .header-about_title {
      font-size: 17px;
   }
   .header-about_paragraph {
      font-size: 9px;
   }
}
</style>