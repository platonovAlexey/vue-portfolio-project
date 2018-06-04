<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>About page title</h1>
      <p class="subtxt">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime, repellat?</p>
      <button>
        <router-link to="/portfolio/one">Look at work</router-link>
      </button>
    </div>
    <div class="right-content">
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus, beatae. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus, beatae.</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus, beatae. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Temporibus, beatae.</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>

.left-content{
  background: #ffe476;
}

.right-content{
  background: #fff;
  padding: 50px;
  margin-top: 80px;
  display: block;
}

button{
  font-size: 1.5em;
  margin-top: 100px;
}

.subtxt{
  font-size: 1.5em;
  margin-top: 30px;
}
</style>
