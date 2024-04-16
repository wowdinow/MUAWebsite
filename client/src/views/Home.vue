<script>
import { RouterLink } from 'vue-router'
// import Home from '../components/Home.vue'


export default {
data(){
  return{
    items: ['Apple', 'Banana', 'Orange']
  }
},

methods: {
  incrementIndex(key){
    return key+1
  }
}
}

</script>

<template>
  <div style="background-color: darkmagenta;" class="vh-100 d-flex flex-column justify-content-center">
    <div class="mx-auto">
    <div class="row text-center">
      <div>
    <!-- <ul>
      <li v-for="item in items" :key="item.id">{{ item.name }}</li>
    </ul> -->
  </div>
      <h1 v-for="(item, index) of items" :key="key" class="animate__animated animate__flipInX animate-duration:2s">
        {{ incrementIndex(index) }}</h1>
      <h1>Welcome to Marsellas Make Up</h1>
    </div>
    <div class="d-flex justify-content-center">
      <RouterLink class="btn btn-primary" to="/details">Get Excited</RouterLink>
    </div>
  </div>
  </div>
</template>
