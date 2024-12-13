<script setup lang="ts">
import { defineProps } from 'vue'

defineProps()

function greet() {
  alert("Hello");
}

</script>

<template>
  <div>
    <h3>Hello There! What is your name?</h3>
    <input></input>
    <button @click="greet">Say Hello</button>
    <img src="" alt="my logo"></img>
  </div>
</template>