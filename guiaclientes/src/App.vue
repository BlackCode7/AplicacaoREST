<template>
  <div id="app">
    <hr>
    <h1>Guia do Cliente</h1>
    <hr>
    <Cliente/>
    <hr>
    <Cliente_2 nome="Anderson Martins" email="anderson@anderson.com" idade="22"/>
  </div>
</template>

<script>
import Cliente_2 from './components/Cliente_2'

export default {  
  name: 'App',
  components: {
    Cliente_2,
   
  }  
}
</script>

<style>

</style>
