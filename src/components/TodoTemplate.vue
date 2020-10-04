<template>
  <div class="TodoTemplate">
    <h1>TodoTemplate</h1>
    <todoInput />
    <TodoList />
  </div>
</template>

<script>
import TodoInput from './TodoInput'
import TodoList from './TodoList'

export default {
  name: "TodoTemplate",
  components: {
    TodoInput,
    TodoList,
  }

}
</script>

<style>
.TodoTemplate {
  background-color: #dedcee;
}
</style>