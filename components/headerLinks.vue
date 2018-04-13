<template>
  <ul>
      <li v-for="page in pages" :key="page.id"><a :href="page.link">{{ page.title }}</a></li>
  </ul>
</template>

<script>
    export default {
        asyncData() {
            pages: [
                {id: '0', title: 'Home', link: '/'},
                {id: '1', title: 'About', link: '/about'},
                {id: '2', title: 'Contact', link: '/contact'},
            ]
        }
    }
</script>