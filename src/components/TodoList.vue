<template>
  <div class="TodoList">
    <TodoListItem />
  </div>
</template>

<script>
import TodoListItem from './TodoListItem'

export default {
  name: "TodoList",
  components: {
    TodoListItem,
  },
}
</script>

<style>
.TodoList {
  background-color: #a5dff9;
}
</style>