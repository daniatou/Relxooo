<template>
     <div class="">
        <div class="my-32 w-[60%] mx-auto ">
        <n-carousel
            effect="card"
            prev-slide-style="transform: translateX(-150%) translateZ(-800px);"
            next-slide-style="transform: translateX(50%) translateZ(-800px);"
            style="height: 240px"
            :show-dots="false"
  >
    <n-carousel-item :style="{ width: '60%' }">
        <div class="bg-white  rounded-[5px] flex items-center justify-center h-[250px] shawdow ">
                <img
                class="carousel-img"
                src="../assets/brand-five-1.webp"
            >
        </div>
    </n-carousel-item>
    <n-carousel-item :style="{ width: '60%' }">
      <img
        class="carousel-img"
        src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel2.jpeg"
      >
    </n-carousel-item>
    <n-carousel-item :style="{ width: '60%' }">
      <img
        class="carousel-img"
        src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel3.jpeg"
      >
    </n-carousel-item>
    <n-carousel-item :style="{ width: '60%' }">
      <img
        class="carousel-img"
        src="https://naive-ui.oss-cn-beijing.aliyuncs.com/carousel-img/carousel4.jpeg"
      >
    </n-carousel-item>
     </n-carousel>
     </div>
     </div>

</template>

<script setup lang="ts">
import { NCarousel, NCarouselItem } from 'naive-ui';
</script>

<style scoped>
.carousel-img {
  margin: 0 auto;
  /* width: 100%;
  height: 100%;
  object-fit: cover; */
}

.shawdow {
    box-shadow: 0 0 40px rgba(51,51,51,.1);
}
</style>