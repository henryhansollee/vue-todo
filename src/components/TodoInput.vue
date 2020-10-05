<template>
  <div class="todo-input">
    <input type="text" class="todo-input-input">
    <button class="todo-input-button">+</button>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.todo-input {
  background-color: #feee7d;
  display: flex;
  padding-top: 3%;
  padding-bottom: 3%;
}
.todo-input-input {
  width: 90%;
  margin-left: 3%;
}
.todo-input-button {
  width: 10%;
  margin-right: 3%;
}
</style>