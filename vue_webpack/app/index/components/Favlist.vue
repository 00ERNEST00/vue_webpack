<template>
    <div v-for="n in 10">{{msg}}</div>

</template>

<script>
    export default {
        data () {
            return {
                msg: 'Hello World!'
            }
        }
    }
</script>

<style>
    html{
        background: cadetblue;
    }
</style>