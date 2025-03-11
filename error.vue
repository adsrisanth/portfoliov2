<template>
    <div class="flex w-screen h-screen bg-black text-slate-50 justify-center">
        <div class="flex justify-center items-center">
            <div class="flex flex-col items-center gap-1.5">
                <span class="border px-3 py-2 rounded-sm border-[#d24306] text-3xl">{{ error.statusCode }} Error</span>
                <span class="text-xl">{{ error.message }}</span>
            </div>
        </div>
    </div>
</template>

<script setup>
    defineProps(['error'])
</script>