<template>
  <div>
    <Head />
    <nuxt-link to="/about">about page</nuxt-link>

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