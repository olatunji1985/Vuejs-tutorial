<template>
    <div class="container">
        <Header title="My Cool Vue App" />
        <button>Add Task</button>
    </div>
</template>

<script>
import Header from "./Header.vue"
export default{
    name:'App',
    components: {
        Header
    }
}

</script>

<style>
#app {
    text-align: center;
    color: blue;
    margin-top: 60px;
}
button {
    padding: 10px 20px;
    font-size: 15px;
    background: blueviolet;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

</style>