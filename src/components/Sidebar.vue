<template>
<nav>
<ul>
  <h3>21w37a</h3>
  <h3>21w38a</h3>
  <h3 selected>21w39a</h3>
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
  padding-left: 1.25em;
  cursor: pointer;
}

nav h3:hover {
  background: hsl(var(--bg-base), 25%);
}

nav h3[selected] {
  background: hsl(var(--bg-base), 18%);
  margin: 0 .5em;
  padding: .75em .25em;
  padding-left: .75em;
  border-radius: 10px;
}

nav h3[disabled] {
  color: hsl(0, 0%, 65%);
  cursor: auto;
}
</style>