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
    max-width: 640px;
    margin: 2rem auto;
    padding: 2rem;
    border-radius: 16px;
    background-color: #101010;
    box-shadow: color-mix(in hsl, var(--primary), rgba(1, 1, 1, 0) 85%) 0 1px 50px;
}

.project-link {
    cursor: pointer;
    text-decoration: underline;
    transition: all .1s;
}
.project-link:hover {
    transition-duration: .1s;
    color: color-mix(in hsl, var(--accent), black 15%);
}

.project-title {
    color: var(--accent);
    text-align: left;
    font-size: 1.2rem;
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
    font-size: 1.0rem;
    font-weight: 700;
}

img {
    width: 100%;
    height: auto;
    border-radius: 16px;
    border: 2px solid var(--accent);
    aspect-ratio: 16 / 9;
}

@media (min-width: 475px) {
    .project-title {
        font-size: 1.3rem;
    }

    .skill-span {
        font-size: 1.1rem;
    }
}

@media (min-width: 640px) {
    .project-title {
        font-size: 1.5rem;
    }

    .skill-span {
        font-size: 1.1rem;
    }
}

@media (min-width: 768px) {
    .project-title {
        font-size: 1.5rem;
    }
}

@media (min-width: 1024px) {
    .project-title {
        font-size: 1.5rem;
    }

    .skill-span {
        font-size: 1.1rem;
    }
}

@media (min-width: 1280px) {
    .project-title {
        font-size: 1.5rem;
    }

    .skill-span {
        font-size: 1.1rem;
    }
}

@media (min-width: 1536px) {
    .project-title {
        font-size: 1.5rem;
    }

    .skill-span {
        font-size: 1.1rem;
    }
}

</style>
