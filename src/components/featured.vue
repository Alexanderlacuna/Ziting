<template>
  <div class=" min-h-screen w-screen px-6 mt-8 ">
      <div class="text-center flex space-x-3 justify-center mb-4 ">

          <h3  class="border-b-4 border-dotted border-red-600 font-semibold">
              FEATURED
          </h3>

          <h3 class="border-b-4 border-solid border-red-600 font-semibold">
              CATERGORIES
          </h3>          

      </div>
        <div class="md:grid md:grid-cols-3  gap-5">
             <div class="control-item">
          <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/shirt.png" alt="" >

          </div>
          <div  class="control-title py-2 bg-red-600 text-white z-30 text-center font-semibold text-xl rounded-lg cursor-pointer">
              African Shirt's
          </div>

          </div>
            <!-- <div class="control-item">
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/dresi.jpg" alt="" >

          </div>
          <div  class="control-title py-2 bg-red-600 text-white z-30 text-center font-semibold text-xl rounded-lg cursor-pointer">
              African Bags
          </div>
          
              

          </div> -->

          <div class="control-item">
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/bag.png" alt="" >

          </div>
          <div  class="control-title py-2 bg-red-600 text-white z-30 text-center font-semibold text-xl rounded-lg cursor-pointer">
              African Bags
          </div>
          
              

          </div>


             <div class="control-item">
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/jewel.png" alt="" >

          </div>
          <div  class="control-title py-2 bg-red-600 text-white z-30 text-center font-semibold text-xl rounded-lg cursor-pointer">
              African Jewelry

          </div>
          
              

          </div>

            <div class="control-item">
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/shoes.png" alt="" >

          </div>
          <div  class="control-title py-2 bg-red-600 text-white z-30 text-center font-semibold text-xl rounded-lg cursor-pointer">
              African Shoes
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
.control-item{
    min-height: 60vh;
    background-color: rgba(3, 3, 3, 0.2);
    margin-bottom: 20px;
    position: relative;
    /* display: flex; */
    

}
.control-image{
   
    
    /* transform: scale(1.2); */
    cursor: pointer;
}
.control-image:hover{
     transform: scale(1.1);
     /* background: #333; */
}
.control-title{
    position: absolute;
    width: 100%;
    bottom: 20%;

}

</style>