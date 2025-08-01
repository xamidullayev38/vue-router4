<template>
    <div class="wrapper">
        <h1>Vue Router App</h1>
        <Navbar/>  
        <router-view/>
    </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue';


</script>


<style>

    *{
        margin: 0;
        padding: 0;
        color: #fff;
    }
    h1{
        text-align: center;
        margin: 20px 0;
    }
    body{
        background: #000;
    }
</style>