<template>
<nav>
<ul>
  <h3>21w37a</h3>
  <h3>21w38a</h3>
  <h3>21w39a</h3>
  <h3>21w40a</h3>
</ul>
</nav>
</template>

<script lang="ts" setup>
</script>

<style scoped>
nav {
  --bg: hsl(var(--bg-base), 22%);
  width: 15em;
}

h3 {
  font-size: 1rem;
  font-weight: normal;
  margin: 0;
}

nav ul {
  padding: 0;
  margin: 0;
  display: flex;
  flex-direction: column;
  gap: .5em;
}

nav h3 {
  display: block;
  padding: .75em;
  cursor: pointer;
}

nav h3:hover {
  background: hsl(var(--bg-base), 25%);
}

nav h3[selected] {
  background: hsl(var(--bg-base), 31%);
}
</style>