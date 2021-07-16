<template>
    <div>
        <input type="text" v-model="title">
        <show-message :title="title" ></show-message>
    </div>
</template>

<script>
import ShowMessage from './ShowMessage.vue'
    export default {
        components:{
            ShowMessage,
        },
        data(){
            return{
                title:'哈哈哈'
            }
        }
    }
</script>

<style scoped>

</style>