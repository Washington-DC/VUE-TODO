<template>
    <div id="app">
        <!--    <img src="./assets/logo.png">-->
        <!--    <router-view/>-->
        <el-container>
            <el-header>Header</el-header>
            <el-main>Main</el-main>
        </el-container>
    </div>
</template>

<script>
    export default {
        name: 'App'
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        /*margin-top: 60px;*/
        max-width: 800px;
        border: 1px solid red;
        margin: 0px auto;
    }

    .el-header {
        line-height: 60px;
        background-color: #2c3e50;

    }
</style>
