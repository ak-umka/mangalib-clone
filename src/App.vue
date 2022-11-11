<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Header from "@/components/Header.vue";
</script>

<template>
  <div class="min-h-screen bg-slate-100">
    <Header />
    <div class="max-w-screen-xl mx-auto">
      <RouterView />
    </div>
  </div>
</template>
