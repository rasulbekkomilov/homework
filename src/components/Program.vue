<script>
   // function extractFileExtension(fullFileName) {
   //    // Faylning to'liq nomini o'zida akslantirgan satr berilgan
   //    // Masalan: /disk/nomi/kataloglar/nomi/fayl.nom.kengaytmasi
   //    // Yuqoridagi misoldagi satrning oxirgi bo'limini izlash
   //    let lastIndex = fullFileName.lastIndexOf('.');
      
   //    if (lastIndex === -1) {
   //       // Agar '.' belgi topilmasa, fayl kengaytmasi mavjud emas
   //       return "Fayl kengaytmasi topilmadi";
   //    } else {
   //       // Agar '.' belgi topilsa, kengaytmani ajratib olamiz
   //       let extension = fullFileName.substring(lastIndex + 1);
   //       return extension;
   //    }
   // }

   // // Test qilish
   // let fileName = "/disk/nomi/kataloglar/nomi/fayl.nom";
   // let fileExtension = extractFileExtension(fileName);
   // console.log("Fayl kengaytmasi:", fileExtension);

</script>

<template>
   <div class="programms w-100 text-center text-white d-flex justify-content-center align-items-center flex-column">
      <h1>Get it on Play Store and download on the App Store</h1>
      <div class="programms-images d-flex justify-content-between mt-5">
         <img src="@/assets/programms-googleplay.png" alt="Google Play Icon">
         <img src="@/assets/programms-appstore.png" alt="App Store Icon">
      </div>
   </div>
</template>

<style scoped>
   .programms {
      margin-top: 30px;
      background-color: #31C5A1;
      height: 371px;
   }
   .programms-images {
      width: 20%;
   }
   .programms > h1 {
      max-width: 700px;
   }
</style>