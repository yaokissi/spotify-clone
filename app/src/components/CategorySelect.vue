<script setup>
import { ref, toRefs } from 'vue';
import { RouterLink} from "vue-router";
import uniqolor from 'uniqolor';

let randColor = uniqolor.random();
randColor.value = uniqolor.random()

const props = defineProps({
    category: String,
    image: String
})
const { category } = toRefs(props)
</script>

<template>

</template>