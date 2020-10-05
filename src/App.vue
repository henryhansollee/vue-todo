<template>
  <div id="app">
    <TodoTemplate />
  </div>
</template>

<script>
import TodoTemplate from './components/TodoTemplate'

export default {
  name: 'App',
  components: {
    TodoTemplate,
  },
}
</script>

<style>
body {
  margin: 0;
  background-color: #D9D4CF;
}
#app {
  display: flex;
  justify-content: center;
}
</style>
