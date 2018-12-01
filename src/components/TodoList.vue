<template>
  <div class="todo_container">
    <TodoInput />
  </div>
</template>

<script>
  import TodoInput from './TodoInput';

  export default {
    name: 'todo-container',
    components: { TodoInput }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .todo_container {
    height: 70%;
    width: 40%;
    background-color: #d3d3d3;
    position: relative;
    border: 1px solid #3f704d;
    border-radius: 10px;
  }
</style>
