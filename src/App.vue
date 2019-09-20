<template>
  <div id="app">
    <div id="wrapper">
      <!--<img alt="Vue logo" src="./assets/logo.png">-->
      <HelloWorld msg="Valg av selskapsform"/>
      <Questionnaire header="myheader"/>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Questionnaire from './components/Questionnaire.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Questionnaire
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
  #wrapper {
    padding-left: 20%;
    padding-right: 20%;
    background-color: aqua;
  }
</style>
