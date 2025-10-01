<script setup>
  import Profile from './components/Profile.vue';
  import LinkButton from './components/LinkButton.vue';
</script>

<template>
  <main>
    <Profile />
    <div class="links-container">
      <LinkButton text="Github" url="https://github.com/damarrsyh" />
      <LinkButton text="Linkedin" url="https://www.linkedin.com/in/damar-ramadiansyah-8224b02aa/" />
      <LinkButton text="Portfolio" url="" />
    </div>
  </main>
</template>

<style>
body {
  margin: 0;
  background-color: #121212;
  font-family: sans-serif;
  color: #e0e0e0;
}

main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  text-align: center;
  padding: 1rem;
  box-sizing: border-box;
}

.links-container {
  margin-top: 2rem;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>