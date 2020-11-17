<template>
    <div>
        <loop-a :count="3"></loop-a>
    </div>
</template>

<script>
    import LoopA from './LoopA.vue';
    export default {
        name: 'LoopDemo',
        components:{
            LoopA
        }
    }
</script>

<style scoped>

</style>