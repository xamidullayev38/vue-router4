<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/counter">Counter</router-link>
  </nav>
</template>

<script setup>

</script>

<style scoped>
    nav{
        width: 100%;    
        padding: 8px 0;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 45px;
    }
    a{
        color: white;
    }
</style>