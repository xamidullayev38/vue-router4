<template>
  <div class="">
    <button @click="decrease">-</button>
  </div>
</template>

<script setup>


  const emit = defineEmits(['decrease'])

  function decrease() {
    emit('decrease')
  }
</script>

<style>

</style>