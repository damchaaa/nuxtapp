<template>
  <div>
    <Navbar></Navbar>
    <main>
      <div class="container">
        <nuxt/>
      </div>
    </main>

  </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue'
  export default {
    components: {
        Navbar
    }
  }
</script>
<style>


*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}


</style>

