<template>
  <section>
    <form>
      <h1>Login page</h1>
      <div class="form-group">
        <input type="text" class="form-control">

      </div>
      <p>
        <nuxt-link to="/home">To home page </nuxt-link>
      </p>
      <button class="btn btn-primary" type="submit">Login</button>
    </form>
  </section>
</template>
<script>
  export default {
      layout: 'empty'
  }
</script>
<style scoped>
  form {
    width: 400px;
    margin: 0 auto;
  }

</style>
