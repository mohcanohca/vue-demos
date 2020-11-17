<template>
    <div>
        <h1>组件A</h1>
        <loop-b v-if="count>0" :bcount="bcount"></loop-b>
    </div>
</template>

<script>
    import LoopB from './LoopB.vue'
    export default {
        name: 'LoopA',
        data(){
            return {
                bcount: this.count-1
            }
        },
        components: {
            LoopB
        },
        props:['count']
    }
</script>

<style scoped>

</style>