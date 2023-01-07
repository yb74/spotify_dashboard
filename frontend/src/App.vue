<script setup lang="ts">

</script>

<template>
  <header>
    <nav class="nav_style">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>
.nav_style a {
  text-decoration: none;
  padding: 1em;
  color: white;
}
</style>
