<template>
  <header>
    <nav>
      <div>
        <h2>Demo NuxtJS</h2>
      </div>
      <ul>
        <li><router-link class="nav-link" to="/">Home</router-link></li>
        <li><router-link class="nav-link" to="/about">About</router-link></li>
        <li><router-link class="nav-link" to="/contact">Contact</router-link></li>
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
    padding: 1em 3em;
    background-color: whitesmoke;
  }

  nav {
    display: flex;
    justify-content: space-between;
  }

  ul {
    display: flex;
    align-items: center;
    gap: 1em;
  }

  li {
    list-style-type: none;
  }

  .nav-link {
    text-decoration: none;
    color: black;
    font-size: 1.2em;
    padding: .2em 1em;
    border-radius: 1em;
  }

  .nav-link:hover{
    background-color: rgba(0, 0, 0, .1);
  }

  .nav-link:active {
    opacity: .8;
  }

</style>
