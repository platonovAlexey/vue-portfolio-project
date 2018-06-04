<template>
  <div class="two main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/one">
        <img src="../assets/arrow-up.svg" alt="arrow" class="arrow arrow-up">
      </router-link>

      <h1>Lorem ipsum</h1>

      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
    
      <router-link to="/portfolio/three">
        <img src="../assets/arrow-down.svg" alt="arrow" class="arrow arrow-down">
      </router-link>
    </div>
    <div class="right-content img2">
      
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

$page_color: #48b886;

h1{
  color: $page_color !important;
}

.img2 {
  background: url('../assets/phone.jpg');
  background-size: cover;
  background-position: 50%;

  img{
    width: 50%;
  }
}

</style>