<script setup>
defineProps({
    to: String,
})
</script>
<template>
    <div class="mt-3">
        <NuxtLink class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium transition-colors focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50 bg-slate-950 text-gray-50 shadow hover:bg-primary/90 px-2 py-1" :to="to"><slot></slot></NuxtLink>
    </div>
</template>
