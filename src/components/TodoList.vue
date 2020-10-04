<template>
  <div>
    <h1>todoList</h1>
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

</style>