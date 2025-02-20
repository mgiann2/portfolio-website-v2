<script setup lang="ts">
    
</script>

<template>
    <nav class="container" role="navigation" aria-label="main navigation">
        <img class="logo" src="/logo.svg" alt="Logo">
        <div class="contact-container">
            <a href="mailto:matteogiannone24@gmail.com" class="btn">Get In Touch</a>
        </div>
    </nav>
</template>

<style scoped>
nav {
    display: flex;
    align-items: center;
    margin-top: 1rem;
}

.container {
    box-sizing: border-box;
}

.logo {
    width: 4rem;
    height: 4rem;
}

.contact-container {
    display: flex;
    flex: 1;
    align-items: center;
    justify-content: flex-end;
}

</style>
