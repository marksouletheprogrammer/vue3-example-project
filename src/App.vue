<template>
  <v-app>
    <v-main>
      <!-- <HelloWorld/> -->
      <AppNavigation />
      <RouterView />
      <AppFooter />
    </v-main>
  </v-app>  
</template>

<script setup lang="ts">
import AppFooter from './components/AppFooter.vue'
import AppNavigation from './components/AppNavigation.vue'
//import HelloWorld from './components/HelloWorld.vue'
</script>
