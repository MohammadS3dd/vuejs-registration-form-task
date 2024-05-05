<script setup>
import Wizard from "@/components/Wizard.vue";
import { ref } from "vue";

const step = ref(0);
</script>

<template>
  <Wizard v-model:step="step" />
</template>

<style scoped lang="scss"></style>
