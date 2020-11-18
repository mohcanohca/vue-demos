<template>
    <div id="app">
      <loop-demo></loop-demo>
      <recursion-demo></recursion-demo>
    </div>
</template>

<script>
    import LoopDemo from './components/Loop/index.vue';
    import RecursionDemo from './components/Recursion/index.vue';

    export default {
        name: 'App',
        components: {
            LoopDemo,
            RecursionDemo
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