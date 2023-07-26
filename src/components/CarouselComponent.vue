<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
    {
        'src': 'disc.jpg',
        'alt': 'Picture 1',
    },
    {
        'src': 'kids.jpg',
        'alt': 'Picture 2',
    },
    {
        'src': 'under.jpg',
        'alt': 'Picture 3',
    },
    {
        'src': 'luxury.jpg',
        'alt': 'Picture 4',
    },
]
</script>
<template>
    <Carousel :pictures="pictures"></Carousel>
</template>
