<script setup lang="ts">
import { pgFn } from "pg1";
pgFn();
</script>

<template>
  <div>
    app
    <h1>子应用👇</h1>
    <!-- name：应用名称, url：应用地址 -->
    <micro-app iframe name="app1-app" url="http://localhost:5174/"></micro-app>
  </div>
</template>

<style scoped></style>
