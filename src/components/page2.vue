<template>
  <button v-on:click="changePage()">點擊我出現page1</button>
</template>

<script setup>
let change = 1;
let changePage = () => {
  let change = 2;
  console.log("被點了:" + change);
  return change;
};

console.log(change);
</script>

<style scoped></style>
