<script setup>
import { ref } from "vue";
import page2 from "./components/page2.vue";
import page1 from "./components/page1.vue";

let change = ref(2);
</script>

<template>
  <page1 v-if="change == 1"></page1>
  <page2 v-if="change == 2"> </page2>
</template>

<style scoped></style>
