<template>
  <v-app dark>
    <Header class="center"/>
    <v-content class="white"> 
        <nuxt class="white" />
    </v-content>
    <Footer />
  </v-app>
</template>
<script src="https://kit.fontawesome.com/a5b5390063.js" crossorigin="anonymous"></script>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'

export default {
  components: {
    Header,
    Footer
  },

}
</script>

<style lang="css">
@import "../assets/style.css";
</style>
