<script>
import { RouterLink } from 'vue-router'
// import Home from '../components/Home.vue'
</script>

<template>
  <div style="background-color: darkmagenta;" class="vh-100 d-flex flex-column justify-content-center">
    <div class="mx-auto">
    <div class="row text-center">
      <h1>Welcome to Marsellas Make Up</h1>
    </div>
    <div class="d-flex justify-content-center">
      <RouterLink class="btn btn-primary" to="/details">Get Excited</RouterLink>
    </div>
  </div>
  </div>
</template>
