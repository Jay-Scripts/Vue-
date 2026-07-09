<script setup lang="ts">
import { ref } from "vue";
import { Button } from "@/components/ui/button";
import { Card, CardContent, CardFooter } from "@/components/ui/card";
import Test from "@/components/pages/Test.vue";

const author = ref("https://www.facebook.com/");
</script>

<template>
  <Test />

  <h1>
    This is authored by <a v-bind:href="author"><span>data</span></a>
  </h1>
</template>

<style scoped></style>
>
