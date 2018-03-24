<template>
  <div>
    <p>Hi! Little app developed with <strong>Nuxt.js</strong>!</p>
    <nuxt-link to="/">Home page</nuxt-link>
  </div>
</template>

<script>
export default {
  asyncData() {
    return {
      
    }
  },
  head: {
    title: 'About page'
  }
}
</script>