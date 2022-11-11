<template>
  <div class="px-4 bg-white rounded mt-5 w-3/4">
    <h1 class="py-4">Popular Manga Updates</h1>
    <div class="flex justify-between">
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Card from "@/components/Card.vue";
export default defineComponent({
  setup() {
    return {};
  },
  components: {
    Card,
  },
});
</script>

<style scoped></style>
