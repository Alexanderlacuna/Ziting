<template>
<div class="min-h-screen w-screen px-5 mt-8 foot-color " >
      <div>
          <h1 class="font-semibold text-xl text-center border-b border-gray-300 py-2">For customers</h1>
         <div>
              <h3 class=" py-2 border-b border-gray-300 ">Orders</h3>
              <h3 class=" py-2 border-b border-gray-300 ">Orders</h3>
              <h3 class=" py-2 border-b border-gray-300 ">Addresses</h3>
              <h3 class=" py-2 border-b border-gray-300 ">Account Details</h3>
         </div>

  </div>

  <div class="mt-5" >
      <div  class="text-center " >

           <h1 class="font-semibold text-xl border-b border-gray-300">Contact Info</h1>  

           <div class="flex  space-x-5 py-2 border-b border-gray-300" >
               <div  class="self-center">
                      <font-awesome-icon class=" border   self-center text-blue-500" style="font-size:20px;"   icon="map-marker-alt"/>
                   <!-- <i class="fas fa-map-marker-alt"></i> -->
               </div>

               <div class="space-x-2 text-center">
                   <h3 class="font-semibold text-left">Address:</h3>
                   <p>Nairobi Kenya</p>
               </div>

           </div>
           <div class="flex  space-x-5 py-2 border-b border-gray-300" >
               <div class="self-center">
                      <font-awesome-icon class=" border   self-center text-blue-500" style="font-size:20px;"   icon="phone-alt"/>
                   <!-- <i class="fas fa-map-marker-alt"></i> -->
               </div>

               <div class="space-x-2 text-center">
                   <h3 class="font-semibold text-left">PhoneNo:</h3>
                   <p>+2541234567</p>
               </div>

           </div>
            <div class="flex  space-x-5 py-2 border-b border-gray-300" >
               <div class="self-center">
                      <font-awesome-icon class=" border   self-center text-blue-500" style="font-size:20px;"   icon="phone-alt"/>
                   <!-- <i class="fas fa-map-marker-alt"></i> -->
               </div>

               <div class="space-x-2 text-center">
                   <h3 class="font-semibold text-left">PhoneNo2:</h3>
                   <p>+2541234567</p>
               </div>

           </div>
               <div class="flex  space-x-5 py-2 border-b border-gray-300" >
               <div class="self-center" >
                      <font-awesome-icon class=" border   self-center text-blue-500" style="font-size:20px;"   icon="envelope"/>
                   <!-- <i class="fas fa-map-marker-alt"></i> -->
               </div>

               <div class="space-x-2 text-center">
                   <h3 class="font-semibold text-left">Email:</h3>
                   <p class="text-center">Zetuafrica@gmail.com</p>
               </div>

           </div>

      </div>
      
  </div>

 
</div>
</template>

<script>
export default {

}
</script>

<style>

.foot-color{
 @apply bg-gray-100
}

</style>