<script setup>
import { ref } from 'vue';
import HomeCard from '../components/HomeCard.vue';
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
    <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here" />
    <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here" />
    <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here" />
    <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here" />
    <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here" />
  </div>
</div>

  <div class="p-8">
    <button class="text-white text-2xl font-semibold hover:underline"
            type="button"

    >
      recommended for you
    </button>
    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here" />
    </div>
  </div>

  <div class="p-8">
    <button class="text-white text-2xl font-semibold hover:underline"
            type="button"

    >
      To make you smarter
    </button>
    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here" />
      <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here" />
    </div>
  </div>

</template>
