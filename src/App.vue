<template>

  <h1><a>Hellow Vue Js!</a></h1>
  <hr />

  <input-task></input-task>
  <input-task></input-task>
  <input-task></input-task>
  <input-task></input-task>
  <task-list></task-list>


</template>
<script>
import InputTask from './components/inputTask.vue'
import TaskList from './components/TaskList.vue'

  export default {
    name: 'App',
    components: {
        InputTask,
        TaskList
    }
  }

</script>
<style scoped>

  h1{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: linear-gradient(to right, #08fa91, #0b51f5);
    text-align: center;
    color: #ffffff;
  }
  hr{
    border:#08fa91 2px solid;
  }

</style>
