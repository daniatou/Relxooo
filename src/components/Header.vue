<template>
    <div class="menu flex justify-between h-[6rem] bg-transparent px-6 text-white items-center text-xl font-semibold border-b-2 border-white">
        <ul class="md:flex space-x-8 hidden">
            <li>Home</li>
            <li class="group relative">
                Pages
                <ul class="sub-list-items hidden group-hover:block">
                    <li>About Us</li>
                    <li>Service</li>
                    <li>Service Details</li>
                    <li>Contact Us</li>
                    <li>Landing Page</li>
                </ul>
            </li>
            <li class="group relative">
                System Page
                <ul class="sub-list-items hidden group-hover:block">
                    <li>Error 404</li>
                    <li>Error 500</li>
                    <li>Backup Unsuscribe</li>
                    <li>Membership Login</li>
                    <li>Membership Register</li>
                    <li>Search Result</li>
                </ul>
            </li>
            <li>Blog</li>
            <li>Contact</li>
            <li>Help</li>
        </ul>
        <div class="logo cursor-pointer">
            <img src="../assets/logo.png" alt="">
        </div>
        <div class=" flex items-center space-x-3">
           <Icon size="28">
                <EarthAmericasFilled  />
           </Icon>
            <span class="hidden md:block">French</span>
            <Icon size="28" class="hidden md:block">
                <Menu/>
            </Icon>
        </div>
        <button class="hidden md:block">
            Get free Consultancy
        </button>
       
    </div>
</template>

<script setup lang="ts">
import { Icon } from '@vicons/utils'
import {EarthAmericasFilled, Menu} from "@vicons/carbon"
</script>


<style scoped>
ul>li:hover{
    color: var(--primary-color);
    cursor: pointer;
}
ul>li {
    padding-top: 20px;
    padding-bottom: 20px;
}
.sub-list-items{
    position: absolute;
    width: 250px;
    background-color: black;
    color: white;
    padding: 20px 30px;
    top: 4.2rem;
    transition: top 3s;
  
}

/* @keyframes sublist-animation {
    100% {top: 4.7rem}
} */


.sub-list-items li{
    padding-top: 10px;
    padding-bottom: 10px;
    font-weight: lighter;
}
.sub-list-items li:hover{
    transform: scale(0.95) translateX(5px);
    transition: all .3s;
}

</style>