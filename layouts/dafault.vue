<template>
  <div id="app">
    <HeaderComponent />

    <Nuxt />

    <FooterComponent />
  </div>
</template>

<script>
  import HeaderComponent from '@/components/HeaderComponent';
  import FooterComponent from '@/components/FooterComponent';

  export default {
    components: {
      HeaderComponent,
      FooterComponent
    }
  }
</script>

<style>

</style>
