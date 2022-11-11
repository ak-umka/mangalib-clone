<template>
  <HotMedia />
  <News />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HotMedia from "@/components/HotMedia.vue";
import News from "@/components/News.vue";

export default defineComponent({
  setup() {
    return {};
  },
  components: {
    HotMedia,
    News,
  },
});
</script>

<style scoped></style>
