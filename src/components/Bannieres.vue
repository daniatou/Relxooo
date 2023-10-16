<template>
    <n-carousel show-arrow autoplay class="w-full text-white overflow-hidden">
        <div class="relative">
            <img
                class="carousel-img"
                src="../assets/slide1.jpg"
            >
            <div class="absolute top-0 bottom-0 left-0 right-0 backdrop-opacity-10 tracking-wide backdrop-invert bg-black/50 h-full w-full flex flex-col justify-center items-center">
                <h1 class=" md:text-8xl text-4xl font-bold animate__animated animate__fadeInUpBig text-center">3 Weeks Unlimited <br> Yoga For Only Free</h1>
                <p class="my-10  text-xl text-center animate__animated animate__fadeInUpBig animate__delay-1s">Specially designed for Yoga School, Yoga Studio and Yoga Online Classes.<br> set up website easy and fast with superior quality.</p>
                <button class="animate__animated animate__fadeInUpBig animate__delay-1s">Browse Our Courses</button>
            </div>
        </div>
        <div class="relative">
            <img
                class="carousel-img"
                src="../assets/slide2.jpg"
            >
            <div class="absolute top-0 bottom-0 left-0 right-0 backdrop-opacity-10 tracking-wide backdrop-invert bg-black/50 h-full w-full flex flex-col justify-center items-center">
                <h1 class=" md:text-8xl text-4xl font-bold animate__animated animate__fadeInUpBig text-center">Unlimited Yoga For  <br> All Levels</h1>
                <p class="my-10 text-xl text-center animate__animated animate__fadeInUpBig">Specially designed for Yoga School, Yoga Studio and Yoga Online Classes. <br> set up website easy and fast with superior quality..</p>
                <button class="animate__animated animate__fadeInUpBig animate__delay-1s">Browse Our Courses</button>
            </div>
        </div>
        <div class="relative">
            <img
                class="carousel-img"
                src="../assets/slide3.jpg">
            <div class="absolute top-0 bottom-0 left-0 right-0 backdrop-opacity-10 tracking-wide backdrop-invert bg-black/50 h-full w-full flex flex-col justify-center items-center">
                <h1 class=" md:text-8xl text-4xl font-bold animate__animated animate__fadeInUpBig text-center">Yoga In Daily Routine  <br> To Stay Fit</h1>
                <p class="my-10 text-xl animate__animated animate__fadeInUpBig text-center">Specially designed for Yoga School, Yoga Studio and Yoga Online Classes.<br> set up website easy and fast with superior quality.</p>
                <button class="animate__animated animate__fadeInUpBig animate__delay-1s">Browse Our Courses</button>
            </div>
        </div>
    </n-carousel>
  </template>

<script setup lang="ts">
import 'animate.css';
import {NCarousel} from 'naive-ui';

</script>

<style scoped>
.carousel-img {
  width: 100%;
  height: 100vh;
  object-fit: cover;
}
button:hover{
   @apply bg-slate-900

}

</style>