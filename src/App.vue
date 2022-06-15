<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <Greet name="Miroslav" heroName="batman" />
  <Greet name="Diana" heroName="megaman"/>
  <Greet name="Clark" heroName="miniman"/>
  <Greet :name="name" :heroName="channel"/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Greet from './components/Greet.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    Greet
  },
  data(){
    return{
      name: 'Vishwas',
      channel: 'Codevolution'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
