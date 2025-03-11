<template>
    <div class="w-screen bg-black p-5">
        <div class="flex flex-row justify-center">
        <div class="flex justify-center">
            <div class="w-[350px] bg-gray-800 rounded-lg p-3">
                <div class="flex flex-row justify-evenly w-full">
                    <NuxtLink to="/"><div class="p-2 hover:bg-gray-700 duration-300 transition-all rounded-sm"><img src="../assets/images/home.svg" width="25px"></div></NuxtLink>
                    <NuxtLink to="/about"><div class="p-2 hover:bg-gray-700 duration-300 transition-all rounded-sm"><img src="../assets/images/home.svg" width="25px"></div></NuxtLink>
                    <NuxtLink to="/services"><div class="p-2 hover:bg-gray-700 duration-300 transition-all rounded-sm"><img src="../assets/images/services.svg" width="25px"></div></NuxtLink>
                    <NuxtLink to="/blogi"><div class="p-2 hover:bg-gray-700 duration-300 transition-all rounded-sm"><img src="../assets/images/home.svg" width="25px"></div></NuxtLink>
                    <NuxtLink to="/"><div class="p-2 hover:bg-gray-700 duration-300 transition-all rounded-sm"><img src="../assets/images/home.svg" width="25px"></div></NuxtLink>
                </div>
            </div>
        </div>
        <div class="absolute right-0">
            <NuxtLink to="/resume">
                <button class="cursor-pointer relative flex items-center px-5 py-2 overflow-hidden font-medium transition-all bg-[#d24306] rounded-md group">
                    <span class="absolute bottom-0 left-0 w-full h-full transition-all duration-500 ease-in-out delay-200 -translate-x-full bg-[#FF4B04] rounded-md group-hover:translate-x-0"></span>
                    <span class="relative w-full text-left text-gray-950 transition-colors duration-200 ease-in-out group-hover:text-gray-950">Resume</span>
                </button>
            </NuxtLink>
        </div>
    </div>
    </div>
</template>