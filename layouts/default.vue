<script setup>
useHead({
    titleTemplate: "%s - avesia3d.com",
    link: [
        {
            rel: "icon",
            href: "/favicon.png",
        },
    ],
})
</script>

<template>
    <div class="font-sans-serif">
        <slot></slot>
    </div>
</template>
