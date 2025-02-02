<script>
import { ref } from 'vue';
import { RouterLink } from "vue-router";

const props = defineProps({
  image: String,
  title: String,
  subTitle: String
})
const { image, title, subTitle } = toRefs(props)

</script>
<template>
<RouterLink to="library"
</template>
