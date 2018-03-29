<template>
  <section>
    <h1>Our products</h1>
    <h2>Exclusively available via us.</h2>
    <input type="text" v-model="productId">
    <button @click="loadProduct">Show Product</button>
    <h3>Or check our newest arrivals:</h3>
    <nuxt-link to="/products/Predators Prey">Predators Prey</nuxt-link>
    <nuxt-link to="/products/Wild Wolf">Wild Wolf</nuxt-link>
  </section>
</template>

<script>
export default {
  data () {
    return {
      productId: ''
    }
  },
  methods: {
    loadProduct() {
      this.$router.push(`/products/${this.productId}`)
    }
  }
}
</script>


