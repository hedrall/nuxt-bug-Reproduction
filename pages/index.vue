<template>
  <section class="container">
      <h1 class="title"></h1>
    <hr>
    <img src="~assets/logo.png" alt="">
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
  h1 {
    background: url( '~assets/logo.png' ) no-repeat top center;
    height: 307px;
  }
</style>
