<template>
  <div>

    <ul>
        <li>Tarefa 1</li><br>
        <li>Tarefa 2</li><br>
        <li>Tarefa 3</li>
    </ul>

  </div>
</template>

<script>
export default {
    name: 'TaskList'
}
</script>

<style>
    ul{
        list-style: none;
        margin: 0;
        padding: 0;
        flex-direction: column;
        text-align: center;
    }
    li{
        background-image: linear-gradient(to right, #08fa91, #0bf5f1);
        color: #fff;
        padding: 10px;
        margin-top: 20px;
        margin-right: 25vw;
        margin-left: 25vw;
        border-radius: 5px;
        cursor: pointer;
        color: #565586;
    }
</style>
