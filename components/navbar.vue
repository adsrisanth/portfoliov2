<template>
    <div class="bg-gray-950 w-screen h-fit">
        <div class="flex justify-between px-5">
            <NuxtLink to="/">
                <div class="text-gray-200">
                    <span class="text-[3.2rem] font-bold">DS</span>
                    <span class="text-[3.2rem] text-teal-600 font-bold">A</span>
                </div>
            </NuxtLink>
            <div class="flex place-items-center justify-center">
                <div class="flex gap gap-5 p-5 text-teal-600">
                    <NuxtLink to="/about"><span>01.<span class="text-gray-200 hover:text-teal-600 cursor-pointer duration-500">About</span></span></NuxtLink>
                    <NuxtLink to="/experience"><span>02.<span class="text-gray-200 hover:text-teal-600 cursor-pointer duration-500">Experience</span></span></NuxtLink>
                    <NuxtLink to="/blog"><span>03.<span class="text-gray-200 hover:text-teal-600 cursor-pointer duration-500">Blogs</span></span></NuxtLink>
                    <NuxtLink to="/contact"><span>04.<span class="text-gray-200 hover:text-teal-600 cursor-pointer duration-500">Contact</span></span></NuxtLink>
                </div>
                <NuxtLink to="/resume">
                    <button class="cursor-pointer relative flex items-center px-5 py-2 overflow-hidden font-medium transition-all bg-teal-500 rounded-md group">
                        <span class="absolute bottom-0 left-0 w-full h-full transition-all duration-500 ease-in-out delay-200 -translate-x-full bg-teal-700 rounded-md group-hover:translate-x-0"></span>
                        <span class="relative w-full text-left text-gray-950 transition-colors duration-200 ease-in-out group-hover:text-gray-950">Resume</span>
                    </button>
                </NuxtLink>
            </div>
        </div>
    </div>
</template>

<script>
import resume from './resume.vue';
</script>