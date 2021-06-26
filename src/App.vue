<template>
  <div id="app">
    <br>
   <Juego/>
  </div>
</template>

<script>
import Juego from './components/juego.vue'
export default {
  name: 'App',
  components: {
   Juego,
  }
}
</script>

<style>
body{
  background-color: #232323;
  margin-top: -20px;
  margin-left: -8px;
  margin-right: -8px;
  font-family: "Montserrat", "Avenir";
}
h1{	font-weight: normal;
	line-height: 1.1;
	padding: 20px 0;
} 
</style>
