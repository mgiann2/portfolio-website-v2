<script setup lang="ts">
import { type Project } from '../helper';
import ProjectCard from './ProjectCard.vue';
import kingsShadowImg from '../assets/kings-shadow.png';
import anovaWebsiteImg from '../assets/anova-website.png';
import sudokuWebsiteImg from '../assets/sudoku-website.png';
import rendererImg from '../assets/renderer.png';

const projects: Project[] = [{
    name: "Vulkan Renderer",
    description: "A 3D physically based deferred renderer written in C# using the Vulkan graphics API. Implements techniques such as image based lighting, omnidirectional shadow maps, and HDR tone mapping.",
    skills: ["Vulkan", "C#", "Graphics"],
    link: "https://github.com/mgiann2/VulkanRenderer",
    img: rendererImg
}, {
    name: "King's Shadow",
    description: "A wave-based horde defense game submitted to the 25th Pirate Software Game Jam. Created using the Godot game engine with C# as the scripting language.",
    skills: ["Godot", "C#", "Game Development"],
    link: "https://mtigo.itch.io/kings-shadow",
    img: kingsShadowImg
}, {
    name: "Anova Test Website",
    description: "A website to perform one-way and two-way anova tests. Built with react and hosted with Netlify.",
    skills: ["React", "Typescript", "HTML", "CSS", "Netlify", "Statistics"],
    link: "https://anovatest.netlify.app/",
    img: anovaWebsiteImg
}, {
    name: "Sudoku Solver Website",
    description: "A website to solve sudoku problems. Solver uses generalized arc consistency to solve boards more efficiently. Built with react and hosted with Netlify.",
    skills: ["React", "Typescript", "HTML", "CSS", "Netlify", "AI"],
    link: "https://supersudokusolver.netlify.app/",
    img: sudokuWebsiteImg
},]
</script>

<template>
    <div class="container">
        <h1 class="section-title">Projects</h1>
        <ProjectCard  v-for="project in projects" :project="project"/>
    </div>
</template>

<style scoped>
.section-title {
    font-size: 1.6rem;
}

@media (min-width: 475px) {
    .section-title {
        font-size: 2rem;
    }
}

@media (min-width: 640px) {
    .section-title {
        font-size: 2rem;
    }
}

@media (min-width: 768px) {
    .section-title {
        font-size: 2rem;
    }
}

@media (min-width: 1024px) {
    .section-title{
        font-size: 3rem;
    }
}

@media (min-width: 1280px) {
    .section-title {
        font-size: 3rem;
    }
}

@media (min-width: 1536px) {
    .section-title {
        font-size: 3rem;
    }
}

</style>
