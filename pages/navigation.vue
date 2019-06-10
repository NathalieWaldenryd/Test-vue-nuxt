<template>
  <nav class="hero-head">
    <nav class="navbar har-background-danger">
      <div class="navbar-brand">
        <nuxt-link to="/">{{ website }}</nuxt-link>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link to="/" class="navbar-item">Home</nuxt-link>
          <nuxt-link to="/about" class="navbar-item">About</nuxt-link>
          <nuxt-link to="/contact" class="navbar-item">Contact</nuxt-link>
        </div>
      </div>
    </nav>
  </nav>
</template>

<script>
export default {
  name: 'Navigation',
  data() {
    return {
      website: 'Test'
    }
  }
}
</script>
