<template>
  <div id="app">
    <Header/>
    <main>
      <MainTop/>
      <MainBotton/>
    </main>
    <footer>
      <FooterTop/>
      <FooterBotton/>
    </footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import MainTop from './components/MainTop.vue';
import MainBotton from './components/MainBotton.vue';
import FooterTop from './components/FooterTop.vue';
import FooterBotton from './components/FooterBotton.vue'

export default {
  name: 'App',
  components: {
    Header,
    MainTop,
    MainBotton,
    FooterTop,
    FooterBotton
  }
}
</script>

<style lang="scss">
@import 'style/varglobal.scss';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
