<template>
  <nav class="nav">
    <nuxt-link
      :to="{name: 'index'}"
      class="logo text-lg"
    >
      👽 Home
    </nuxt-link>
    <nuxt-link to="/about">About Page</nuxt-link>
    <nuxt-link to="/blog">Posts Page</nuxt-link>
  </nav>
</template>

<script>
export default {}
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  align-items: center;
  margin-bottom: 70px;
  font-weight: lighter;
  letter-spacing: 0.5px;
}
</style>
