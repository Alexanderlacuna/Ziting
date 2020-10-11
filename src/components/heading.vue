<template>


<div class="bg-set bg-center"  :style="{'background-image': 'url(' + require('@/assets/img/african.png') + ')'}" >
<div class="bg-black bg-opacity-50 control-h text-white
flex  w-screen" >
    <div class="h-full control-w flex flex-col justify-center  mx-auto md:px-10 ">

      <h3 class="text-3xl md:text-5xl text-center md:text-left ">African Stock Products</h3>
      <h3 class="texl-xl md:text-2xl text-center">we got all  collections for you</h3>

      <div class="space-x-4 space-y-4 text-center">
          <button class="btn bg-transparent">
              Shop  Now
          </button>

          <button class="btn color-coral">
              Discover now
          </button>
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
.bg-set{
    height:80vh;
}
.control-h{
    min-height:100%;
}

.color-coral{
    background:coral;

}
.btn{
    @apply px-8 ;
    @apply py-3;
    border: 1px solid #fff;
    @apply rounded-lg
}
.control-w{
    max-width: 1100px;

}



</style>