<template>
    <div>
        <h1>第{{count}}次调用</h1>
        <recursion v-if="count < 3" :count="count+1"></recursion>
    </div>
    
</template>

<script>
    export default {
        name: 'Recursion',
        props:['count']
    }
</script>

<style scoped>

</style>