<template>
  <header>
    <nav>
      <div>
        <h2>Tutorial NuxtJS</h2>
      </div>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
  export default {
    name: 'HeaderComponent'
  }
</script>

<style>
  header {
    padding: 1.5em 3em;
  }

  nav {
    display: flex;
    justify-content: end;
  }

  ul {
    display: flex;
    /* justify-content: end; */
    align-items: center;
    gap: 2em;
  }

  li {
    list-style-type: none;
  }
</style>
