<template>
    <div>
        <div class="">
            <navbar/>
        </div>
        <div class="container">

            <router-view></router-view>
        </div>
    </div>
</template>

<script>
    import Navbar from "./components/Navbar";

    export default {
        name: 'App',
        components: {
            Navbar
        }
    }
</script>

<style>
    @import '~materialize-css/dist/css/materialize.min.css';
</style>
