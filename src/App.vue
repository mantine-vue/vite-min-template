<script setup lang="ts">
import "@mantine-vue/core/styles.css";
import { MantineProvider } from "@mantine-vue/core";
import { theme } from "./theme";
</script>

<template>
  <MantineProvider :theme="theme">App</MantineProvider>
</template>
