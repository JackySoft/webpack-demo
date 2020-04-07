<template>
    <div class="app">
        <h1>欢迎学习webpack4.42知识</h1>
        <p>{{title}}</p>
        <p>欢迎关注：前端未来，关乎你的未来</p>
        <img src="/imgs/qrcode.jpg" alt="">
    </div>
</template>
<script>
    export default {
        name:'app',
        data(){
            return {
                title:'Hello Vue'
            }
        }
    }
</script>  
<style lang="scss">
    .app{
        text-align: center;
        span{
            display: inline-block;
            width:300px;
            height: 300px;
            background: url('/imgs/qrcode.jpg') no-repeat;
            background-size: 300px;
        }
    }
</style>