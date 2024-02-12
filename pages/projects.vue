<script setup>
useSeoMeta({
    title: "Projects",
    description: "our projects"
})
</script>

<template>
    <div class="mt-24 w-full max-w-xl px-5 mx-auto">
        <h1 class="mb-3 text-center text-xl font-bold">Projects by avesia3d</h1>
        <ProjectList>
            <ProjectCard>
                <ProjectTitle>avesia Canvas</ProjectTitle>
                <ProjectDesc>
                    The ultimate drawing app.
                </ProjectDesc>
                <ProjectButton to="https://www.canvas.ac">
                    Open website
                </ProjectButton>
            </ProjectCard>
            <ProjectCard>
                <ProjectTitle>adaptor-rs</ProjectTitle>
                <ProjectDesc>
                    Building a reactive modern UI with rust.
                </ProjectDesc>
                <ProjectButton to="https://adaptor.rs">
                    Open website
                </ProjectButton>
            </ProjectCard>
            <ProjectCard>
                <ProjectTitle>winui3-rs</ProjectTitle>
                <ProjectDesc>
                    winui3 in rust
                </ProjectDesc>
                <ProjectButton to="https://github.com/doraidamon/winui3-rs">
                    GitHub
                </ProjectButton>
            </ProjectCard>
            <ProjectCard>
                <ProjectTitle>Coming soon</ProjectTitle>
                <ProjectDesc>
                    
                </ProjectDesc>
            </ProjectCard>
        </ProjectList>
    </div>
</template>
