<script setup lang="ts">
    
</script>

<template>
    <nav role="navigation" aria-label="main navigation">
        <div class="container">
            <h1 style="width: min-content;
                       letter-spacing: -5px;
                       background: linear-gradient(90deg, var(--primary), var(--accent));
                       -webkit-background-clip: text;
                       background-clip: text;
                       color: transparent;
                       font-size: 3.2rem;
                       margin: 0">
                MG
            </h1>
            <div class="contact-container">
                <a href="mailto:matteogiannone24@gmail.com" class="btn">Get In Touch</a>
            </div>
        </div>
    </nav>
</template>

<style scoped>
nav {
    margin: 2rem 0;
}

nav > .container {
    display: flex;
    align-items: stretch;
}

.contact-container {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    flex-grow: 1;
}

@media only screen and (max-width: 600px) {
    nav {
        margin: 1rem 0;
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
