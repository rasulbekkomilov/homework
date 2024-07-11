<script>

</script>

<template>
      <!-- <div class="card pt-5 align-items-center text-center" style="width: 18rem;">
         <div class="card-body align-items-center">
            
         </div>
      </div>
      <div class="card pt-5 align-items-center text-center" style="width: 18rem;">
         <div class="card-body">
            
         </div>
      </div>
      <div class="card pt-5 d-flex align-items-center text-center" style="width: 18rem;">
         <div class="card-body">
            
         </div>
      </div>  -->
      
      <div class="container">
         <div class="cards d-flex flex-wrap justify-content-between my-5">
            <div class="card d-flex align-items-center justify-content-center card1 mb-3">
               <img class="card-img-top img-fluid w-25" src="@/assets/card-1.png" alt="Card image cap">
               <h5 class="card-title">Set up an account</h5>
               <p class="card-text">Download the app for free, sign up and verify your account.</p>
            </div>
            <div class="card d-flex align-items-center justify-content-center card2">
               <img class="card-img-top img-fluid w-25" src="@/assets/card-2.png" alt="Card image cap">
               <h5 class="card-title">Apply for a loan</h5>
               <p class="card-text">Apply for a loan and our technology will run a credit score and decide if you are qualified. </p>
            </div>
            <div class="card d-flex align-items-center justify-content-center card3 mt-3">
               <img class="card-img-top img-fluid w-25" src="@/assets/card-3.png" alt="Card image cap">
               <h5 class="card-title">Get your cash</h5>
               <p class="card-text">If you qualify, your loan will be disbursed to your wallet.</p>
            </div>
         </div>
      </div>
   </template>
<style scoped>
   .card {
      text-align: center;
      border: none !important;
      border: 1px solid gray !important;
   }
   .card-text {
      font-size: 15px;
   }
   .card1 {
      border-radius: 0px !important;
      border-top: 10px solid blue !important;
   }
   .card2 {
      border-radius: 0px !important;   
      border-top: 10px solid #FF814A !important;
   }
   .card3 {
      border-radius: 0px !important;   
      border-top: 10px solid #31C5A1 !important;
   }
   .cards > .card {
      width: 288px;
      height: 327px;
   }
   @media (max-width:769px) {
      .cards {
         display: flex !important;
         flex-direction: column !important;
         align-items: center !important;
         justify-content: center !important;
      }
   }
</style>