<template>
  <div id="app">
    <div>
      <Header/>
      <Main/>
      <ActionsBar/>
      <Footer/>
      <SocialBar/>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import ActionsBar from './components/ActionsBar.vue';
import Footer from './components/Footer.vue';
import SocialBar from './components/SocialBar.vue';


export default {
  name: 'App',
  components: {
    Header,
    Main,
    ActionsBar,
    Footer,
    SocialBar,
  }
}
</script>

<style lang="scss">
@import '~bootstrap';

</style>
