<template>
  <div id="app">
	<h1>Test</h1>
	<draggable-thing></draggable-thing>
  </div>
</template>

<script>
import DraggableThing from './components/DraggableThing.vue'

export default {
  name: 'App',
  components: {
	DraggableThing,
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
