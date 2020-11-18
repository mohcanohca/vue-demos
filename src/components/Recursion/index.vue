<template>
    <div>
        <h1>组件递归调用</h1>
        <recursion :count="0"></recursion>
    </div>
    
</template>

<script>
    import Recursion from './Recursion.vue';
    export default {
        name: 'RecursionDemo',
        props:['count'],
        components: {
            Recursion
        }
    }
</script>

<style scoped>

</style>