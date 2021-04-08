<template>
  <div data-app>
    <SampleEditor />
  </div>
</template>

<script>
import SampleEditor from './components/SampleEditor.vue'

export default {
  name: 'App',
  components: {
    SampleEditor
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  max-width:900px;
  width:100%;
  padding:12px;
  margin-left:auto;
  margin-right:auto;
}
</style>
