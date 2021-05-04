<template>
  <div id="app">
   <!-- HEADER -->
   <Header/>
   <!-- MAIN CONTENT -->
   <Main/>
   <!-- FOOTER -->
   <Footer/>
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}


a {
  text-decoration: none;
}

ul {
  list-style: none;
}

.container {
  max-width: 1170px;
  margin: 0 auto;
}

</style>
