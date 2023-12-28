<template>
  <main>
    <header>
      <div>
        <div class="w-full flex justify-between p-4">
          <div class="flex gap-5 justify-center items-center">
            <img
              src="~/assets/images/icon-menu.svg"
              alt="Sneakers logo"
            >
            <img
              src="~/assets/images/logo.svg"
              alt="Sneakers logo"
            >
          </div>
          <div class="flex gap-5 justify-center items-center">
            <img
              src="~/assets/images/icon-cart.svg"
              alt="Sneakers logo"
            >
            <img
              src="~/assets/images/image-avatar.png"
              alt="Sneakers logo"
              class="w-8 h-8"
            >
          </div>
        </div>
      </div>
    </header>
    <NuxtTailwindLightbox :image-list="imageList" />
    <div class="w-full p-5">
      <h4 class="text-primary-orange uppercase font-bold text-sm tracking-wider">
        Sneaker Company
      </h4>
      <h1 class="text-3xl font-bold text-neutral-very-dark-blue">
        Fall Limited Edition Sneakers
      </h1>
      <p class="mt-2 text-neutral-dark-grayish-blue">
        These low-profile sneakers are your perfect casual wear companion. featuring a durable rubber outer sole,
        they'll withstand everything the weather can offer.
      </p>
      <div class="w-full justify-between flex mt-2">
        <div class="flex items-center gap-4">
          <span class="text-3xl font-bold text-neutral-very-dark-blue leading-tight">$125.00</span>
          <span class="text-primary-orange font-bold bg-primary-orange/15 px-3 py-0.5 rounded-lg">50%</span>
        </div>
        <span class="font-bold text-neutral-grayish-blue line-through">$250.00</span>
      </div>
      <div class="w-full bg-neutral-light-grayish-blue h-0.5 p-6 rounded-lg mt-4 flex justify-between items-center">
        <img
          src="~/assets/images/icon-minus.svg"
          alt="Minus"
        >
        <span class="font-bold text-neutral-very-dark-blue">0</span>
        <img
          src="~/assets/images/icon-plus.svg"
          alt="Minus"
        >
      </div>
      <div class="w-full bg-primary-orange shadow-xl shadow-primary-orange/30 p-4 rounded-lg mt-4">
        <div class="w-full flex justify-center items-center gap-4">
          <svg
            width="22"
            height="20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M20.925 3.641H3.863L3.61.816A.896.896 0 0 0 2.717 0H.897a.896.896 0 1 0 0 1.792h1l1.031 11.483c.073.828.52 1.726 1.291 2.336C2.83 17.385 4.099 20 6.359 20c1.875 0 3.197-1.87 2.554-3.642h4.905c-.642 1.77.677 3.642 2.555 3.642a2.72 2.72 0 0 0 2.717-2.717 2.72 2.72 0 0 0-2.717-2.717H6.365c-.681 0-1.274-.41-1.53-1.009l14.321-.842a.896.896 0 0 0 .817-.677l1.821-7.283a.897.897 0 0 0-.87-1.114ZM6.358 18.208a.926.926 0 0 1 0-1.85.926.926 0 0 1 0 1.85Zm10.015 0a.926.926 0 0 1 0-1.85.926.926 0 0 1 0 1.85Zm2.021-7.243-13.8.81-.57-6.341h15.753l-1.383 5.53Z"
              fill="white"
            />
          </svg>
          <p class="text-white font-bold">
            Add to cart
          </p>
        </div>
      </div>
    </div>
  </main>
</template>

<script setup lang="ts">
import image1 from '@/assets/images/image-product-1.jpg';
import image2 from '@/assets/images/image-product-2.jpg';
import image3 from '@/assets/images/image-product-3.jpg';
import image4 from '@/assets/images/image-product-4.jpg';

const imageList = ref([image1, image2, image3, image4]);
</script>
