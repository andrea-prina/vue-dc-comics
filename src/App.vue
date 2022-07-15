<template>
  <div id="app">
    <div class="wrapper">
      <Header/>
      <Main/>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';


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
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .wrapper {
    width: 80%;
    min-width: 1000px;
    margin: 0 auto;
  }

</style>
