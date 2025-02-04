<script setup>
import CategorySelect from "@/components/HomeCard.vue";

</script>
<template>
  <div class="p-8">
    <button class="text-white text-2xl font-semibold hover:underline"
            type="button"

    >
      Podcasts To make you a better developer
    </button>
    <div class="py-1.5"></div>

    <div class="flex items-center">
      <CategorySelect  category="Podcasts" image="https://picsum.photos/id/40/300/300"  />
    </div>
  </div>
</template>

