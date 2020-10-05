<template>
  <div class="TodoTemplate">
    <h1 class="todo-title">vue-todo</h1>
    <h6 class="todo-author">henryhansollee</h6>
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
  background-color: #60c5ba;
  margin-top: 10%;
  width: 25%;
}
.todo-title {
  text-align: center;
}
.todo-author {
  text-align: end;
  margin-right: 4%;
}
</style>