<script setup lang="ts">
    
</script>

<template>
    <nav role="navigation" aria-label="main navigation">
        <div class="container">
            <h1 style="width: min-content;
                       letter-spacing: -5px;
                       background: linear-gradient(135deg, var(--primary), var(--accent));
                       -webkit-background-clip: text;
                       background-clip: text;
                       color: transparent;">
                MG
            </h1>
            <div class="contact-container">
                <a href="mailto:matteogiannone24@gmail.com" class="btn">Get In Touch</a>
            </div>
        </div>
    </nav>
</template>

<style scoped>
nav > .container {
    display: flex;
    min-height: 3.25rem;
    align-items: stretch;
}

.contact-container {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    flex-grow: 1;
}

</style>
