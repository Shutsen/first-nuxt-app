<template>
  <div>
    <the-navigation></the-navigation>
    <h1>This part of the USERS page is coming from the CUSTOM users layout</h1>
    <nuxt/>
  </div>
</template>

<script>
import TheNavigation from '@/components/TheNavigation'
export default {
  components: {
    TheNavigation
  }
}
</script>

<style>
</style>
