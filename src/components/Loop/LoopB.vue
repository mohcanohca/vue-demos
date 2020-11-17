<template>
    <div>
        <h1>组件B</h1>
        <loop-a v-if="bcount>=0" :count="bcount"></loop-a>
    </div>
</template>

<script>
    export default {
        name: 'LoopB',
        components: {
            // webpack 异步 import
            LoopA:  () => import('./LoopA.vue')
        },
        props:['bcount']
    }
</script>

<style scoped>

</style>