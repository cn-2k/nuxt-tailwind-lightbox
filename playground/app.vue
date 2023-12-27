<template>
  <div class="w-full flex flex-col items-center h-screen justify-center">
    <div class="text-3xl lg:text-3xl font-bold tracking-wide text-center">
      <a
        href="https://github.com/cn-2k/vue-tailwind-lightbox"
        target="_blank"
      >Vue Tailwind Lightbox ✨</a>
    </div>
    <ImageGallery :image-list="imageList" />
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'

import image1 from '@/assets/images/image-product-1.jpg'
import image2 from '@/assets/images/image-product-2.jpg'
import image3 from '@/assets/images/image-product-3.jpg'
import image4 from '@/assets/images/image-product-4.jpg'

const imageList = ref([image1, image2, image3, image4])
</script>
