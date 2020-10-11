<template>
  <nav>
      <v-toolbar app>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
          <v-toolbar-title>
              <span>Ninja</span>
          </v-toolbar-title>

      </v-toolbar>
      <v-navigation-drawer   v-model="drawer" app class="indigo">
          <p>test</p>

      </v-navigation-drawer>
  </nav>
</template>

<script>
export default {

    data(){
        return {
            drawer:true
        }
    }

}
</script>

<style>

</style>