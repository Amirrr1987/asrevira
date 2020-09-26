<template>
  <body id="app" class="app">
    <Header/>
    <Main/>
    <Footer/>
    <a href="#" class=""><img src="@/assets/img/support.svg" title="" alt="" class="support"></a>
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