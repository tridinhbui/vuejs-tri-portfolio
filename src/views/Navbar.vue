<!-- Navbar.vue -->
<template>
  <nav>
    <img src="https://via.placeholder.com/50x50" alt="Tri logo" />
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About Me</router-link></li>
      <li><router-link to="/contact">Contact Me</router-link></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style>
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem;
}

nav img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
}

nav ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

nav li {
  margin: 0 1rem;
}

nav a {
  color: #fff;
  text-decoration: none;
}
</style>
