<template>
  <div class="home">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <img class="banner" src="../assets/banner.webp">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style scoped>
  .banner {
    margin: 0;
    width: 100%;
  }
  
</style>