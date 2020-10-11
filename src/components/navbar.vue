<template>
<div class="nav">
    <div class="control-nav  border-b border-gray-300 space-x-4">
        <div class="flex px-1 md:px-10  py-2 space-x-1 md:space-x-4 text-sm md:font-semibold">
        <h3>My Account</h3>
        <h3>Login/Register</h3>
        <h3>Orders</h3>
        <h3>Track Order</h3>
        <h3>Wishlist</h3>
        </div>
    </div>

 
  
    <div class="flex justify-between control-h border-b border-gray-500 ">    
     <div class="flex  space-x-2 md:space-x-3 self-center px-10 ">
          <div class="self-center cursor-pointer">
              <font-awesome-icon icon="bars"/>
          </div>
         <h3 class="text-xl font-bold">Zetu</h3>
         
     </div>


    <div class="hide-display md:flex   md:px-4 justify-evenly self-center space-x-4
    uppercase">
       <div class="hover:text-yellow-700 border-b-1 border-yellow-500">
            <h3>HOME</h3>
       </div>
        <div class="hover:text-yellow-700 border-b-1 border-yellow-500">
             <h3>SHOP</h3>
        </div>
         <div class="hover:text-yellow-700 border-b-1 border-yellow-500">
              <h3>ABOUT US</h3>
         </div>

         <div class="hover:text-yellow-700 border-b-1 border-yellow-500">
               <h3>Contact Us</h3>
        
         </div>
        <div class="hover:text-yellow-700 border-b-1 border-yellow-500">
             <h3>My Account</h3>
        </div>
    
            <!-- <i class="fas fa-shopping-cart"></i> -->
            <div>
                 <font-awesome-icon icon="shopping-cart" />
            </div>

             <div>
                <font-awesome-icon icon="search"/>
            </div>
<!-- <i class="fas fa-bars"></i> -->


          
            <!-- <font-awesome-icon :icon="['fas', 'fa-shopping-cart']" /> -->
       
     
            
             
    </div>
</div>
    <!-- <nav>
      <v-toolbar app>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
          <v-toolbar-title>
              <span>Ninja</span>
          </v-toolbar-title>

      </v-toolbar>
      <v-navigation-drawer   v-model="drawer" app class="bg-white">
          <v-card
    class="mx-auto mt-5"
    max-width="300"
    tile
  >
    <v-list shaped>
      <v-subheader>REPORTS</v-subheader>
      <v-list-item-group v-model="item" color="primary">
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
        >
          <v-list-item-icon>
            <v-icon v-text="item.icon"></v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title v-text="item.text"></v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-item-group>
    </v-list>
  </v-card>

      </v-navigation-drawer>
  </nav>
 -->




</div>
</template>

<script>
  export default {
    data: () => ({
      drawer:false,
      item: 1,
      items: [
        { text: 'Real-Time', icon: 'mdi-clock' },
        { text: 'Audience', icon: 'mdi-account' },
        { text: 'Conversions', icon: 'mdi-flag' },
      ],
    }),
  }
</script>
<style>
.control-h{
    /* background:#333; */
    height:56px;
    /* color:white; */
    
}
.control-nav{
    /* height:32px; */
}
.hide-display{
    display: none;
    
}
.nav{
    position: relative;
}
.openBar{
    /* position: absolute; */
    z-index: 20;
    background: #fff;
    width: 100%;
    transition: 1s;
    transition-property: all;
    transition-timing-function: ease-in-out;
    min-height: 0px;
    
    /* display:none; */
}
@media(max-width: 600px){
    .control-nav{
        display:none;
    }
}
</style>