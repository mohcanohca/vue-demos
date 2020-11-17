<template>
    <div id="app">
      <loop-demo></loop-demo>
    </div>
</template>

<script>
    import LoopDemo from './components/Loop/index.vue'

    export default {
        name: 'App',
        components: {
            LoopDemo
        }
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>