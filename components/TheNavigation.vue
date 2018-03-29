<template>
  <div class="links">
    <nuxt-link to="/">Home</nuxt-link>
    <nuxt-link to="/users">Users</nuxt-link>
    <nuxt-link to="/products">Products</nuxt-link>
  </div>
</template>

<script>
export default {
  
}
</script>


<style scoped>
  .links {
    text-align: center;
    background-color: rgb(46, 45, 45);
    padding: 15px;
  }

  .links a {
    color: white !important;
    font-weight: bold;
  }
</style>

