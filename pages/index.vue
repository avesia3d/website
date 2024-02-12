<script setup>
useSeoMeta({
    title: "avesia",
    description: "A creator collective" 
})
</script>

<template>
    <div>
        <div class="flex items-center justify-end px-3 pt-3">
            <NuxtLink to="/projects" class="px-1 py-0.5 bg-slate-950 text-gray-50 text-sm">Projects</NuxtLink>
        </div>
        <div class="mt-24 w-full max-w-xl px-5 mx-auto">
            <div class="flex justify-center items-center gap-7">
                <img class="h-24" src="/avesia3d3.svg" />
            </div>
            <h1 class="my-5 text-lg text-center">avesia3d: a creator collective</h1>
            <div>
                <Heading>Our design philosophy of creative software</Heading>
                <Heading2>No obstacle</Heading2>
                <Paragraph><b>It's free.</b> ― Works well as open source alternative of expensice commercial software.</Paragraph>
                <Paragraph><b>Community-driven.</b> - A software grows with community.</Paragraph>
                <Paragraph><b>No ugly ads.</b> - Also we don't track you.</Paragraph>
                <Heading2>Create anywhere</Heading2>
                <Paragraph><b>Platform independent.</b> ― Run anywhere with low resources. Capable with any screen.</Paragraph>
                <Heading2>Respect your rights</Heading2>
                <Paragraph><b>Your work is your work.</b> ― Your work won't be used without agreement.</Paragraph>
                <Heading2>Customizable</Heading2>
                <Paragraph><b>Refine your tool.</b> ― Boost your productivity with a customized workflow.</Paragraph>
            </div>
        </div>
    </div>
</template>
