<template>
  <BC64FilePicker 
  text="Clique aqui para enviar um arquivo" 
  text-color="#4b5563" 
  icon-color="#4b5563"
  border-color="#cacaca" 
  @base64result="value => console.log(value)" />
</template>

<script>
import BC64FilePicker from './components/BC64FilePicker.vue'


export default {
  name: 'App',
  components: {
    BC64FilePicker
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
