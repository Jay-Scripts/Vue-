<script setup lang="ts">
import { ref } from "vue";
import { Button } from "@/components/ui/button";
import { Card, CardContent, CardFooter } from "@/components/ui/card";
import Test from "@/components/pages/Test.vue";
const isBtnDisabled = ref(true);
const author = ref("https://www.facebook.com/");
</script>

<template>
  <h1>
    This is authored by <a v-bind:href="author"><span>data</span></a>
  </h1>

  <button
    class="border p-5 bg-blue-100 hover:cursor-pointer disabled:cursor-not-allowed disabled:bg-gray-400"
    :disabled="isBtnDisabled"
  >
    Click
  </button>
</template>

<style scoped></style>
