<template>
  <nav>
    <router-link id="router-link" to="/">
    <div class="menu-item"><a href="#">Home</a></div>
    </router-link>
  </nav>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style lang="scss" scoped>
  nav {
    padding: 30px;
  }
</style>
