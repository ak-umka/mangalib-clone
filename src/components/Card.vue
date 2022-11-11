<template>
  <div class="grid grid-cols-1 pb-4">
    <div class="rounded overflow-hidden w-[126px] relative">
      <img
        class="w-full"
        src="https://picsum.photos/seed/picsum/400/600"
        alt="Sunset in the mountains"
      />
      <div class="text-white absolute bottom-[12px] px-2">TOM 2</div>
    </div>
    <div class="whitespace-normal">manga</div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  setup() {
    return {};
  },
});
</script>

<style scoped></style>
