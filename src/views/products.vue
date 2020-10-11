<template>
  <div class="min-h-screen w-screen mt-8">
     <div class="py-10 control-bg px-6" >
          <h3 class=" text-lg"> Clothing</h3>
         
      </div>
      <div>
          <div>
            <h3  class="py-2 px-6">
                Default Sorting
            </h3>
          </div>
          <div>
              <interesting/>
          </div>
      </div>
  </div>
</template>

<script>
import interesting from "@/components/interesting.vue"
export default {
    components:{
        interesting
    }

}
</script>

<style>

.control-bg{

      background-color: rgba(3, 3, 3, 0.2);
}

</style>