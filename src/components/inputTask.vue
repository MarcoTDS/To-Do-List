<template>

    <div id="in-task">
        <input type="text">
        <button>add</button>
    </div>

</template>

<script>

    export default {
        name: 'InputTask'
    }

</script>

<style>
    
        #in-task{
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 20px;
        }
    
        #in-task input{
            width: 300px;
            height: 30px;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 0 10px;
        }
    
        #in-task button{
            width: 100px;
            height: 30px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-left: 10px;
            background-color: #08fa91;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
        }
</style>

