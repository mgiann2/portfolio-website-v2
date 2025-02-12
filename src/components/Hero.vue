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
    margin: 8rem 0;
}

.title {
    background: transparent;
    background: linear-gradient(90deg, var(--primary), var(--accent));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    font-size: 5rem;
    line-height: 1.2em;
    margin: 0;
}

.tag-line {
    font-size: 2rem;
    line-height: 1.2em;
    font-weight: 400;
    margin-top: 1em;
}

@media only screen and (max-width: 600px) {
    .title {
        font-size: 2rem;
    }

    .tag-line {
        font-size: 1.2rem;
    }
}

@media only screen and (min-width: 600px) {
    
}

@media only screen and (min-width: 768px) {
    
}

@media only screen and (min-width: 992px) {
    
}

@media only screen and (min-width: 1200px) {
    
}

@media only screen and (min-width: 1400px) {
    
}
</style>
