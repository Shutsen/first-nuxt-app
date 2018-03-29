<template>
  <section>
    <p>Go ahead, input the person you would love to know more about, below:</p>
    <input type="text" v-model="userId">
    <button @click="loadUser">Show User</button>
    <nuxt-child/>
  </section>
</template>

<script>
export default {
  data () {
    return {
      userId: ''
    }
  },
  methods: {
    loadUser() {
      this.$router.push(`/users/${this.userId}`)
    }
  },
  layout: 'users'
}
</script>

