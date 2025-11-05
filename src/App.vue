<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </nav>

  <router-view />
</template>

<style scoped>
nav {
  display: flex;
  gap: 1rem;
  justify-content: center;
  margin-top: 2rem;
}
a.router-link-active {
  font-weight: bold;
  text-decoration: underline;
}
</style>
