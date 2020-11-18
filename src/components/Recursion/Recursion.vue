<template>
    <div>
        <h1>第{{count}}次调用</h1>
        <recusion v-if="count < 3" :count="count+1"></recusion>
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