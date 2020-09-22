<template>
  <body id="app">
    <Header/>
    <Main/>
    <Footer/>
  </body>
</template>
<script>
import Header from '@/views/Header';
import Main   from '@/views/Main';
import Footer from '@/views/Footer';
export default {
  name: 'App',
  components:{
    Header,
    Main,
    Footer,
  }
}
</script>