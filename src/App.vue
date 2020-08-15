<template>
    <div id="app">
        <div id="my">
            <router-link to="/">go to index</router-link>
            <br>
            <router-link to="/help">go to my todo list</router-link>
        </div>
        <router-view></router-view>
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
    margin-top: 60px;
}
</style>
