<template>
    <header class="bg-[#2d3b48]">
        <nav class="container flex mx-auto px-6 py-4 items-center">
            <RouterLink to="/" class="flex gap-1 items-center">
                <img src="/pawn_logo.svg" alt="logo" class="w-12 md:w-16 drop-shadow-lg">
                <h1 class="text-2xl text-white font-extrabold font-serif md:text-4xl drop-shadow-lg">KingBoard</h1> 
            </RouterLink>

            <RouterLink to="/" class="mr-0 font-bold font-mono ml-auto p-2 bg-[#c9d8d3] rounded md:p-3 text-gray-900">
                Login
            </RouterLink>
        </nav>
    </header>
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>

<style scoped>
</style>
