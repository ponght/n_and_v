
<template>
<div class="con-center">

    <h1> Hello {{ name }}</h1>
    <input type="text" v-binnd:value="name">
</div>
</template>

<script>
    export default{
        data(){
            return {
                name: "Artdvp"
            }
        }
    }
</script>

<style>
    .con-center{
        text-align: center ;
        margin-top:  1rem ;
    }
</style>


