<script setup lang="ts">

</script>

<template>
    <div class="container">
        <div class="hero-div">
            <h1 class="title">Software Developer.</h1>
            <h1 class="title">Problem Solver.</h1>
            <h2 class="tag-line">Pursuing code with craftsmanship.</h2>
        </div>
    </div>
</template>

<style scoped>
.hero-div {
    margin: 7rem 0;
}

.title {
    background: transparent;
    background: linear-gradient(90deg, var(--primary), var(--accent));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    font-size: 2rem;
    line-height: 1.2em;
    margin: 0;
}

.tag-line {
    font-size: 1.2rem;
    line-height: 1.2em;
    font-weight: 400;
    margin-top: 1em;
}

@media (min-width: 475px) {
    .title {
        font-size: 2.5rem;
    }

    .tag-line {
        font-size: 1.5rem;
    }
}

@media (min-width: 640px) {
    .title {
        font-size: 3rem;
    }
}

@media (min-width: 768px) {
    .title {
        font-size: 4rem;
    }

    .tag-line {
        font-size: 2.2rem;
    }
}

@media (min-width: 1024px) {
    .title {
        font-size: 4rem;
    }

    .tag-line {
        font-size: 2.2rem;
    }
}

@media (min-width: 1280px) {
    .title {
        font-size: 5rem;
    }

    .tag-line {
        font-size: 3rem;
    }
}

@media (min-width: 1536px) {
    .title {
        font-size: 5rem;
    }

    .tag-line {
        font-size: 3rem;
    }
}
</style>
