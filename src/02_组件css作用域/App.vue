<template>
    <div id="App">
        <h2 class="title">APP</h2>
        <hello-world></hello-world>
    </div>
</template>

<script>
import HelloWorld from './HelloWorld.vue'
    export default {
        components:{
            HelloWorld
        }
    }
</script>

<style scoped>
 .title{
     color: blue;
 }
 h2{
     color: red;
 }
</style>