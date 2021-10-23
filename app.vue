<template>
  <p>{{ counter }}</p>
  <button @click="onClick1">click me</button>
</template>

<script setup lang="ts">
import { ref } from "vue";
const counter = ref(0);

function onClick1() {
  console.log("onClick1");
  counter.value++;
}
function onClick2() {
  console.log("onClick2");
  counter.value++;
}
</script>
