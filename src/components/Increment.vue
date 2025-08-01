<template>
  <div class="">
    <button @click="plus">+</button>
  </div>
</template>

<script setup>

    const emit = defineEmits(['plus'])
    function plus() {
        emit('plus')
    }
</script>

<style>

</style>