<script setup lang="ts">
import profilePhoto from '../assets/profile.jpg'
</script>

<template>
    <div style="position: relative;">
        <div class="custom-shape-divider-top-1739562910">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" class="shape-fill"></path>
                <path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" class="shape-fill"></path>
                <path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" class="shape-fill"></path>
            </svg>
        </div>
    </div>
    <div class="color-container">
        <div class="container">
            <div class="about-div">
                <h1 class="greeting">Hi, my name is Matteo</h1>
                <p class="about-content">I’m a recent graduate in Computer Science and Statistics from the University of Toronto, driven by an enthusiasm for software development and a deep curiosity for how things work. During my university career, I’ve worked on a variety of projects, including developing a full stack recipe web app with rich social features, building and training machine learning models, and writing my own terminal shell in C that supported basic UNIX commands. Outside of school, I am constantly exploring new technologies and topics, such as Vulkan for graphics programming, to become a more experienced and well-rounded developer.
                </p>
                <img :src="profilePhoto">
            </div>  
        </div>
    </div>
</template>

<style scoped>
.color-container {
    background-color: var(--primary);
    background-image: linear-gradient(180deg, var(--primary), var(--accent));
    padding-top: calc(5rem + 64px);
    padding-bottom: 5rem;
}

.greeting {
    font-size: 1.6rem;
    margin-top: 0;
    margin-bottom: 3rem;
}

.about-div {
    margin-right: auto;
    margin-left: auto;
    max-width: 1000px;
}

.about-content {
    margin-top: 0;
    margin-bottom: 3rem;
}

.custom-shape-divider-top-1739562910 {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.custom-shape-divider-top-1739562910 svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 64px;
}

.custom-shape-divider-top-1739562910 .shape-fill {
    fill: var(--black);
}

img {
    border-radius: 16px;
    aspect-ratio: 1 / 1;
    max-width: 15rem;
    margin: 0 auto;
}

@media (prefers-color-scheme: light) {
    .greeting {
        color: var(--white);
    }

    .about-content {
        color: var(--white);
    }

    .custom-shape-divider-top-1739562910 .shape-fill {
        fill: var(--white);
    }
}

@media (min-width: 475px) {
    .greeting {
        font-size: 2rem;
    }
}

@media (min-width: 640px) {
    .greeting {
        font-size: 2rem;
    }
}

@media (min-width: 768px) {
    .greeting {
        font-size: 2rem;
    }
}

@media (min-width: 1024px) {
    .greeting {
        font-size: 3rem;
    }

    .custom-shape-divider-top-1739562910 svg {
        height: 128px;
    }

    .color-container {
        padding-top: calc(5rem + 128px);
    }

    .about-content {
        font-size: 1.2rem;
    }
}

@media (min-width: 1280px) {
    .greeting {
        font-size: 3rem;
    }

    .custom-shape-divider-top-1739562910 svg {
        height: 128px;
    }

    .color-container {
        padding-top: calc(5rem + 128px);
    }

    .about-content {
        font-size: 1.2rem;
    }
}

@media (min-width: 1536px) {
    .greeting {
        font-size: 3rem;
    }

    .custom-shape-divider-top-1739562910 svg {
        height: 128px;
    }

    .color-container {
        padding-top: calc(5rem + 128px);
    }

    .about-content {
        font-size: 1.2rem;
    }
}

</style>
