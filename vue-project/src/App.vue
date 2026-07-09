<script setup lang="ts">
import { ref } from "vue";
import { Button } from "@/components/ui/button";
import { Card, CardContent, CardFooter } from "@/components/ui/card";
import Test from "@/components/pages/Test.vue";
const stringInterpolate = ref("long long string");
const year = ref("2021");
year.value = "2023";
// const products = [
//   {
//     id: 1,
//     name: "Wireless Headphones",
//     price: "$89.99",
//     image: "https://placehold.co/400x300",
//   },
//   {
//     id: 2,
//     name: "Smart Watch",
//     price: "$149.99",
//     image: "https://placehold.co/400x300",
//   },
//   {
//     id: 3,
//     name: "Mechanical Keyboard",
//     price: "$99.99",
//     image: "https://placehold.co/400x300",
//   },
//   {
//     id: 4,
//     name: "Gaming Mouse",
//     price: "$49.99",
//     image: "https://placehold.co/400x300",
//   },
// ];
</script>

<template>
  <Test />
  <h1>{{ stringInterpolate }} is interporated</h1>
  <p>{{ year }}</p>
</template>

<style scoped></style>
>
