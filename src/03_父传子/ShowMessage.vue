<template>
    <div>
        <h2>{{title}}</h2>
        <p>{{content}}</p>
    </div>
</template>

<script>
    export default {
        props:{
            title:String,
            content:{
                type:String,
                require:true,
                default:'there is no '
            }
        }
    }
</script>

<style scoped>

</style>