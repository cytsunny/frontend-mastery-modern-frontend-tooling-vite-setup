<script setup lang="ts">
  function greet () {
    alert("Hello");
  }

</script>

<template>
  <div>
    <h3>Hello There! What is your name?</h3>
    <input></input>
    <button @click="greet">Say Hello</button>
  </div>
</template>

