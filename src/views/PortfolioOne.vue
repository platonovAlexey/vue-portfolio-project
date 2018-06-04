<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>Lorem ipsum</h1>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
    
      <router-link to="/portfolio/two">
        <img src="../assets/arrow-down.svg" alt="arrow" class="arrow arrow-down">
      </router-link>
    </div>
    <div class="right-content img2">
      <img src="../assets/logo.svg" alt="logo">
    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'one',
  components: {
    HelloWorld
  }
}
</script>

<style scoped lang="scss">

$page_color: #625B7E;

h1{
  color: $page_color !important;
}

.img2 {
  background: $page_color;

  img{
    width: 50%;
  }
}

</style>