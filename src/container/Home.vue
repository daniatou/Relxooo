<template>
    <div class="h-[100vh] relative overflow-hidden">
        <div class="absolute z-30 w-full">
            <Header/>
        </div>
        <div class="absolute top-0">
            <Bannieres/>
        </div>
    </div>
   
</template>

<script setup lang="ts">
import Header from '../components/Header.vue'
import Bannieres from '../components/Bannieres.vue'

</script>