<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
  {
    'src': '/sepatu1.jpg',
    'alt': 'Picture 1',
  },
  {
    'src': '/sepatu2.jpg',
    'alt': 'Picture 2',
  },
  {
    'src': '/sepatu3.jpg',
    'alt': 'Picture 3',
  },
]
</script>
<template>
  <Carousel :pictures="pictures"></Carousel>
</template>
