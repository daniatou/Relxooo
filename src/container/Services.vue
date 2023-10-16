<template>
    <div class="w-full packages ">
        <div class=" flex flex-col items-center w-[90%] mx-auto py-[100px] ">
            <div>
                <h4 class="text-4xl font-bold tracking-wide text-center">Popular Yoga Service</h4>
                <p class="text-lg tracking-wide text-center my-4">Many desktop publish packages web page editors now use model text <br> search for sites their infancy.</p>
            </div>
            <div class="flex flex-col md:flex-row md:space-x-12 space-y-4 md:space-y-0 my-12 justify-center">
                <div class="flex flex-col space-y-3 md:w-[400px] w-[300px]">
                    <div class="relative group1 group ">
                        <img class="rounded-t-[4px] w-full" src="../assets/yoga1.webp" alt="">
                        <div class="price w-[5rem] h-[5rem] rounded-full bg-primary-color flex items-center justify-center font-bold text-white text-3xl">
                            $30
                        </div>
                    </div>
                    <div class="bg-white rounded-b-[4px] h-[12rem] p-6">
                        <n-tag class="mb-2" type="warning"> Meditation</n-tag>
                        <h5 class="text-2xl font-bold my-5 hover:text-[#fc410e]  cursor-pointer">Hatha Yoga</h5>
                       <div class="desc flex justify-between">
                            <span class="text-gray-600 tracking-widest md:text-lg text-xs">
                                <Icon size="20">
                                    <Calendar/>
                                </Icon>
                                24.07.2022
                            </span>
                            <span class="text-gray-600 tracking-widest md:text-lg text-xs">
                                <Icon size="20">
                                    <Time />
                                </Icon>
                                01:00AM-02:00PM
                            </span>
                       </div>
                    </div>
                </div>
                <div class="flex flex-col space-y-3 md:w-[400px] w-[300px]">
                    <div class="relative group1 group ">
                        <img class="rounded-t-[4px] w-full" src="../assets/yoga2.webp" alt="">
                        <div class="price w-[5rem] h-[5rem] rounded-full bg-primary-color flex items-center justify-center font-bold text-white text-3xl">
                            $30
                        </div>
                    </div>
                    <div class="bg-white rounded-b-[4px] h-[12rem] p-6">
                        <n-tag class="mb-2" type="info"> Karma Yoga</n-tag>
                        <h5 class="text-2xl font-bold my-5 hover:text-[#fc410e]  cursor-pointer">Smart Flow Yoga Course</h5>
                       <div class="desc flex justify-between">
                            <span class="text-gray-600 tracking-widest md:text-lg text-xs">
                                <Icon size="20">
                                    <Calendar/>
                                </Icon>
                                24.07.2022
                            </span>
                            <span class="text-gray-600 tracking-widest md:text-lg text-xs">
                                <Icon size="20">
                                    <Time />
                                </Icon>
                                01:00AM-02:00PM
                            </span>
                       </div>
                    </div>
                </div>
                <div class="flex flex-col space-y-3 md:w-[400px] w-[300px]">
                    <div class="relative group1 group ">
                        <img class="rounded-t-[4px] w-full" src="../assets/yoga3.webp" alt="">
                        <div class="price w-[5rem] h-[5rem] rounded-full bg-primary-color flex items-center justify-center font-bold text-white text-3xl">
                            $30
                        </div>
                    </div>
                    <div class="bg-white rounded-b-[4px] h-[12rem] p-6">
                        <n-tag class="mb-2" type="success">Power Yoga </n-tag>
                        <h5 class="text-2xl font-bold my-5 hover:text-[#fc410e]  cursor-pointer">Earth Power Yoga Course</h5>
                       <div class="desc flex justify-between">
                            <span class="text-gray-600 tracking-widest md:text-lg text-xs">
                                <Icon size="20">
                                    <Calendar/>
                                </Icon>
                                24.07.2022
                            </span>
                            <span class="text-gray-600 tracking-widest md:text-lg text-xs">
                                <Icon size="20">
                                    <Time />
                                </Icon>
                                01:00AM-02:00PM
                            </span>
                       </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>

<script setup lang="ts">
import { NTag } from 'naive-ui';
import {Calendar, Time} from '@vicons/carbon'
import { Icon } from '@vicons/utils';

</script>

<style scoped>
.price{
    position: absolute;
    right: 20px;
    top: 20px;

}
.packages {
    background-image: url('../assets/services-bg.webp');
}

.desc span {
    display: flex;
    align-items: center;
}

.group {
    cursor:pointer;
    overflow: hidden;
}

.group1:hover img{
    transform: scale(1.1);
    transition: all 1s;
}
</style>