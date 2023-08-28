<template>
  <div>
    <HeaderComponent></HeaderComponent>
    <main>
      <h1>Welcome Nuxt</h1>
      <p>This is a demo web for task purposed</p>
      <p>The real website will be build soon</p>
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
    display: flex;
    justify-content: center;
    align-content: center;
    flex-direction: column;
    gap: 1em;
    margin-top: 4em;
  }
</style>
