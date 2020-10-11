<template>
  <v-app>
   <div>
      <div>
      <!-- <router-link to = "/home">Router Link 1</router-link>
       -->
      <!-- <div class="fixed z-50 w-screen bg-white shadow-lg">
         <navbar/>
      </div> -->
      <!-- <navigation/> -->
       <navbar/>
    </div>
    <div>
      <router-view></router-view>
        
     
    </div>

  
    
   </div>
  </v-app>
</template>

<script>
// import navigation from "@/components/navigation.vue"
import navbar from "@/components/navbar.vue"


export default {
  name: "App",

  components: {
     navbar
    //  navigation
  },

  data: () => ({
    //
  })
};
</script>
<style scoped>
.control-footer{
  position: absolute;
  width:100%;
  bottom: 0;
  background: red;
}
</style>