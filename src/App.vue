<template>
    <div id="app">
        <h1>Calculadora</h1>
        <Calculator />
    </div>
</template>

<script>
import  Calculator from "./main/Calculator"

export default {
    components: { Calculator }
}
</script>

<style>
body {
    margin: 0;
}

#app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: black;
    background: linear-gradient(to right, rgb(83, 105, 119), rgb(41,46,73))
}
</style>