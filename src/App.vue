<script setup>
import { RouterLink, RouterView,useRoute } from 'vue-router'
const route = useRoute();
</script>

<template>
  <div>

    <header class="bg-white shadow">
      <div class="wrapper">
    
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>

      </nav>
    </div>
  </header>
  
  </div>
  
  <RouterView />
</template>

<style>

</style>
