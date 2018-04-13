<template>
  <h1>Contact</h1>
</template>
<template>
  <div>
    <Head />
    <nuxt-link to="/about">about page</nuxt-link>
    <nuxt-link to="/contact">contact page</nuxt-link>

    <Foot />
  </div>
</template>

<script>
import Head from "../components/header"
import Foot from "../components/footer"

export default {
  components: {
    Head,
    Foot
  }
}
</script>