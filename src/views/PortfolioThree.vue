<template>
  <div class="three main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/two">
        <img src="../assets/arrow-up.svg" alt="arrow" class="arrow arrow-up">
      </router-link>

      <h1>Lorem ipsum</h1>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero, quia?</p>
    
    </div>
    <div class="right-content img2">
    </div>
  </div>
</template>

<script>

export default {
  name: 'three'
}
</script>

<style scoped lang="scss">

$page_color: #5487a8;

h1{
  color: $page_color !important;
}

.img2 {
  background: url('../assets/card.jpg');
  background-size: cover;
  background-position: 50%;

  img{
    width: 50%;
  }
}

</style>