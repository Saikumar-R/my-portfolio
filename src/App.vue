<template>
  <div id="main">
    <NavigationBar />
    <MainContent />
    <Footer />
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar/NavigationBar.vue'
import MainContent from './components/main/Main-content.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
   NavigationBar,
   MainContent,
   Footer
  }
}
</script>

<style lang="scss">
body{
  margin: 0px;
  #app{
    // height: 100vh;
    // widows: 100vw;
    background-color: rgb(32, 32, 33);
  }
  h1, h2, h3, h4{
    margin-top: 0px;
  }
}
</style>
