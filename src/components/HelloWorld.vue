<script setup lang="ts">
import JsxImgTag from "./JsxImgTag";

function greet() {
  alert("Hello");
}
</script>

<template>
  <div>
    <JsxImgTag />
    <h3>Hello There! What is your name?</h3>
    <input />
    <button @click="greet">Say Hello</button>
  </div>
</template>
