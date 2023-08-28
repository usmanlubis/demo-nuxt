<template>
  <div>
    <HeaderComponent></HeaderComponent>
    <main>
      <h1>This is About page</h1>
    </main>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>
  export default {
    name: 'IndexPage'
  }
</script>

<style>
  *,
  *::before,
  *::after {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }

  body {
    background-color: #282A35;
    min-height: 100vh;
    padding-bottom: 40px;
  }

  main {
    color: whitesmoke;
    text-align: center;
    margin-top: 4em;
  }
</style>
