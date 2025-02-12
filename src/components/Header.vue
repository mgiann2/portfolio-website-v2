<script setup lang="ts">
    
</script>

<template>
    <nav class="container" role="navigation" aria-label="main navigation">
        <h1 class="logo">
            MG
        </h1>
        <div class="contact-container">
            <a href="mailto:matteogiannone24@gmail.com" class="btn">Get In Touch</a>
        </div>
    </nav>
</template>

<style scoped>
nav {
    display: flex;
    align-items: stretch;
    margin-top: 1rem;
}

.logo {
    width: min-content;
    letter-spacing: -5px;
    background: linear-gradient(90deg, var(--primary), var(--accent));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    font-size: 3.2rem;
    margin: 0;
}

.contact-container {
    display: flex;
    flex: 1;
    align-items: center;
    justify-content: flex-end;
}

</style>
