<template>
  <div>
    <h3>{{ title }}</h3>
    <div>
      <img src="../assets/image/css-icon 1.png" alt="css" />
      <p>{{ desc }}</p>
    </div>
  </div>
</template>

<script setup>
import { defineProps } from "vue";
const props = defineProps({
  title: {
    type: String,
    default: "",
  },
  desc: {
    type: String,
    default: "",
  },
});
</script>

<style scoped></style>
