<template>
  <div class="">
    <h2>Counter page</h2>
    <p>{{ title }}</p>
    <Descr @decrease="title > 0 ? title-- : '' " />
    <Increment @plus="incr"/>
  </div>
</template>

<script setup >
    import { ref,reactive } from 'vue';
    import Descr from '../components/Descr.vue'
    import Increment from '../components/Increment.vue'
    const title = ref(0)


    function incr() {
        title.value++
    }
</script>

<style>
    button{
        color: black;
    }
</style>