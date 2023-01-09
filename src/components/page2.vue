<template>
  <button v-on:click="changePage()">點擊我出現page1</button>
</template>

<script setup>
let changePage = () => {
  console.log("被點了");
};
</script>

<style scoped></style>
