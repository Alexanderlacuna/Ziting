<template>
  <div class=" min-h-screen w-screen px-6 mt-8">
      <div class="text-center flex space-x-3 justify-center mb-4 ">

          <h3  class="border-b-4 border-dotted border-red-600 font-semibold">
              TOP
          </h3>

          <h3 class="border-b-4 border-solid border-red-600 font-semibold">
              INTERESTING
          </h3>          

      </div>

      <div class="grid grid-cols-2  gap-4 my-5">
          <div class="text-center font-semibold text-red-700">
            <h3 >Newest</h3>
          </div>

          <div class="text-center font-semibold">
              <h3>Featured</h3>

          </div>

          <div class="text-center font-semibold">
              <h3>Best Sellers</h3>
          </div>
          <div class="text-center font-semibold">
              Cheapest
          </div>
          

      </div>

      <div class="md:grid md:grid-cols-3 md:gap-3">
             <div>

             <div class="control-item">
            <div class="control-hover-item px-2 py-1 rounded-lg">
             <!-- <font-awesome-icon icon="heart"/> -->
            <div class="flex space-x-1 cursor-pointer" >
                 <font-awesome-icon  class="self-center" icon="heart"/>
                
                <h3>Add to wishlist</h3>
            </div>

            </div>
          <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/shirt.png" alt="" >

          </div>
         

          <div class="control-view py-2  font-semibold text-lg cursor-pointer">
              <!-- <h3>Quick view</h3> -->
               <router-link to="/product">  <span class="text-white">Quick view</span> </router-link>
              
          </div>

          </div>
          <div class="my-4 text-center border-b border-gray-800 py-2">
              <h3 class="font-semibold underline">African  shirt</h3>
              <h3 class="font-bold text-red-600">Ksh:1500</h3>

          </div>


       </div>

          <div>
              <div class="control-item">
                <div class="control-hover-item px-2 py-1 rounded-lg">
             <!-- <font-awesome-icon icon="heart"/> -->
            <div class="flex space-x-1 cursor-pointer" >
                 <font-awesome-icon  class="self-center" icon="heart"/>
                
                <h3>Add to wishlist</h3>
            </div>

            </div>
              
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/bag.png" alt="" >

          </div>
            <div class="control-view py-2  font-semibold text-lg  cursor-pointer">
              <h3>Quick view</h3>
          </div>
         
          
              

          </div>
            <div class="my-4 text-center border-b border-gray-800 py-2">
              <h3 class="font-semibold underline">African  Handbag</h3>
              <h3 class="font-bold text-red-600">Ksh:1500</h3>

          </div>
          </div>
           
          



           <div>
                 <div class="control-item">
                  <div class="control-hover-item px-2 py-1 rounded-lg">
             <!-- <font-awesome-icon icon="heart"/> -->
            <div class="flex space-x-1 cursor-pointer" >
                 <font-awesome-icon  class="self-center" icon="heart"/>
                
                <h3>Add to wishlist</h3>
            </div>

            </div>
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/bag.png" alt="" >

          </div>
         
          
              

          </div>
            <div class="my-4 text-center border-b border-gray-800 py-2">
              <h3 class="font-semibold underline">African  Handbag</h3>
              <h3 class="font-bold text-red-600">Ksh:1500</h3>

          </div>
           </div>
          

        <div>
                <div class="control-item">
                 <div class="control-hover-item px-2 py-1 rounded-lg">
             <!-- <font-awesome-icon icon="heart"/> -->
            <div class="flex space-x-1 cursor-pointer" >
                 <font-awesome-icon  class="self-center" icon="heart"/>
                
                <h3>Add to wishlist</h3>
            </div>

            </div>
                <div>
              <img  class="transition-all ease-in-out duration-150 control-image" src="@/assets/img/shoes.png" alt="" >

          </div>
          
          
          </div>
            <div class="my-4 text-center border-b border-gray-800 py-2">
              <h3 class="font-semibold underline">African  Shoes</h3>
              <h3 class="font-bold text-red-600">Ksh:1500</h3>

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
.control-hover-item{
    position: absolute;
    right: 10px;
    top: 5px;
    /* padding-right: 5px; */
    background: red;
    z-index: 10;
    color:white;
}
.control-view{
    position: absolute;
    bottom: 2px;
    width: 100%;
    text-align: center;
    background: #333;
    opacity: 0.7;
    color:white
    
}
.control-view:hover{
    background: black;
}
</style>