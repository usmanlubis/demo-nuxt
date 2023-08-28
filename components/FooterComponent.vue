<template>
  <footer>
    <p>&copy; {{ new Date().getFullYear() }} <a href="https://github.com/usmanlubis" target="_blank" class="footer-link">Usman Lubis</a> - All rights reserved. Made with Nuxt3</p>
  </footer>
</template>

<script>
  export default {
    name: 'FooterComponent',
  }
</script>

<style>
  footer {
    height: 40px;
    background-color: whitesmoke;
    position: absolute;
    bottom: 0;
    width: 100%;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .footer-link {
    color: unset;
  }
</style>
