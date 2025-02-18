<script setup lang="ts">
import { type Project } from '../helper';

defineProps<{project: Project}>();
</script>

<template>
    <div class="project-div">
        <img :src="project.img" alt=""/>
        <h2 class="project-title"><a :href="project.link" target="_blank" class="project-link">{{project.name}}</a></h2>
        <p class="project-description">{{project.description}}</p>
        <div class="skills-div"><span class="skill-span" v-for="skill in project.skills">{{skill}}</span></div>
    </div>
</template>

<style scoped>
.project-div {
    max-width: 720px;
    margin: 2rem auto;
    padding: 2rem;
    border-radius: 16px;
    background-color: color-mix(in srgb, var(--primary), transparent 90%);
}

.project-link {
    cursor: pointer;
}

.project-title {
    text-align: left;
}

.project-description {
    text-align: left;
    line-height: 1.7rem;
}

.skills-div {
    display: flex;
    align-items: center;
    justify-content: left;
    flex-wrap: wrap;
    gap: 1rem;
}

.skill-span {
    text-align: left;
    color: var(--accent);
    font-size: 1.1rem;
    font-weight: 700;
}

img {
    width: 100%;
    height: auto;
    border-radius: 16px;
    /* border: 2px solid var(--accent); */
    aspect-ratio: 16 / 9;
}

</style>
