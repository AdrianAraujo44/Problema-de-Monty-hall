<template>
    <div id="app">
        <h1>Problema de Monty Hall</h1>
        <Gift />
    </div>
</template>

<script>
import Gift from '.component/Gift'
export default {
    name:'App',
    components:{ Gift }
}
</script>

<style>
    *{
        box-sizing : border-box;
        font-family: 'Montserrat', sans-serif;
        background: linear-gradient(to right, #c33764, #1d2671);
    }
    #app {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    #app h1 {
        border: 1px solid black;
        background-color:#0004;
        padding: 20px;
        margin-bottom: 60px;
    }
</style>
