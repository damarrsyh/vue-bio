<script setup>
    defineProps({
        text: String,
        url: String
    })
</script>

<template>
    <a :href="url" target="_blank" class="link-button">
        {{ text }}
    </a>
</template>

<style scoped>
.link-button {
    display: block;
    background-color: #42b883;
    color: white;
    text-decoration: none;
    padding: 1rem 2rem;
    margin: 0.5rem 0;
    border-radius: 8px;
    width: 80%;
    max-width: 400px;
    font-weight: bold;
    transition: transform 0.2 ease-in-out;
}

.link-button:hover {
    transform: scale(1.05);
}
</style>