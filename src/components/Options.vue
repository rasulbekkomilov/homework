<script setup>

</script>

<template>

   <div class="container d-flex align-items-center">
      <div class="header-image w-50">
         <img class="img-fluid" src="@/assets/terms-img.png" alt="Header Image">
      </div>
      <div class="header-about w-50">
         <h1 class="header-about_title text-lg-">Save on your own terms</h1>
         <p class="header-about_paragraph">Savings give you financial options</p>
         <div class="d-flex w-75 image-container justify-content-between">
            <div class="google-icon w-50 img-fluid">
               <img class="google-icon w-75 img-fluid" src="@/assets/play-market-icon.png" alt="Play Market Icon">
            </div>
            <div class="appstore-icon w-50 img-fluid">
               <img class="appstore-icon w-75 img-fluid" src="@/assets/appstore-icon.png" alt="AppStore Icon">
            </div>
         </div>
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