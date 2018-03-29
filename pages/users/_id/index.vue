<template>
  <h1>This is the page for user {{$route.params.id}}</h1>
</template>

<script>
export default {
  validate (data) {
    console.log(data)
    // only accept when input is 1:
    return data.params.id == 1
    // or only accept numbers:
    // /^\d+$/.test(data.params.id)
  }
}
</script>