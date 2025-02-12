<script setup lang="ts">
import profilePhoto from '../assets/profile.jpg'
</script>

<template>
    <div class="container">
        <h1 class="greeting">Hi, my name is Matteo</h1>
        <div class="about-picture-div">
            <div class="about-div">
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab similique ea sit libero id! Itaque obcaecati, aperiam ab sint voluptate nulla molestiae impedit facilis perferendis nihil doloribus. Beatae, sequi voluptate.
                </p>
            </div>
            <img :src="profilePhoto" alt="Picture of Matteo" class="picture" />
        </div>
    </div>
</template>

<style scoped>
p {
    font-size: 1.1rem;
}

.greeting {
    font-size: 1.6rem;
}

.about-picture-div {
    display: flex;
    flex-direction: row-reverse;
    gap: 3rem;
    flex-direction: column;
}

.about-div {
    padding: 3rem;
    background: color-mix(in hsl, var(--accent), transparent 90%);
    border-radius: 16px;
    text-align: left;
}

.about-div > p {
    margin: 0;
}

img {
    border-radius: 16px;
    aspect-ratio: 1 / 1;
    max-width: 300px;
    margin: 0 auto;
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
        font-size: 3rem;
    }
}

@media (min-width: 1024px) {
    .greeting {
        font-size: 3rem;
    }

    .about-picture-div {
        padding: 0 6rem;
        flex-direction: row-reverse;
    }
}

@media (min-width: 1280px) {
    .greeting {
        font-size: 3rem;
    }

    .about-picture-div {
        padding: 0 8rem;
        flex-direction: row-reverse;
    }
}

@media (min-width: 1536px) {
    .greeting {
        font-size: 3rem;
    }

    .about-picture-div {
        padding: 0 10rem;
        flex-direction: row-reverse;
    }
}

</style>
