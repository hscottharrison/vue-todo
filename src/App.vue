<template>
  <div id="app">
    <TodoList />
  </div>
</template>

<script>
  import TodoList from './components/TodoList';


  export default {
    name: 'app',
    data: {
      todoItems: []
    },
    components: { TodoList }
  }
</script>

<style>
  #app {
    height: 100vh;
    width: 100vw;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
