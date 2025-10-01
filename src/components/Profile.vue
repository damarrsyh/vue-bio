<script setup>
    import profileImage from '../assets/hysna.png'
</script>

<template>
    <img :src="profileImage" alt="Hysna Profile" width="150">
    <h1>Damar Ramadiansyah</h1>
    <p>Saya ada orang yang sedang belajar vue untuk frontend developer</p>
</template>

<style scoped>
img {
    border: 50%;
    border: 4px solid #42b883;
    margin-bottom: 1rem;
}

h1 {
    margin: 0;
    font-size: 1rem;
    color: #FFFFFF;
}

p {
    margin-top: 0.5rem;
    font-size: 1rem;
    color: #a0a0a0;
}
</style>