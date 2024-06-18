<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Présentation</RouterLink>
        <RouterLink to="/competences">Portefeuille de compétences</RouterLink>
        <RouterLink to="/projects">Projets</RouterLink>
      </nav>
    </div>
  </header>

  <article>
    <RouterView />
  </article>
</template>

<style scoped>
header {
  display: flex;
  line-height: 1.5;
  max-height: 100vh;
  position: fixed;
  top: 0;
  right: 0;
  left: 0;
  background-color: var(--vt-c-black);
  z-index: 1;
  justify-content: center;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}

main {
  margin-top: 100px;
  margin-bottom: 50px;
}

article {
  margin-left: auto;
  margin-right: auto;
  width: 1280px;
}
</style>
