<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>Lorem, ipsum dolor.</h1>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
    </div>
    <div class="right-content img1">
      <button><router-link to="/portfolio/one">Browser Work</router-link></button>
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

.img1 {
  background: url('../assets/home.jpg')
}

</style>
