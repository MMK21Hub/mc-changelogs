<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import Sidebar from './components/Sidebar.vue'; 
</script>

<template>
<Sidebar>
  
</Sidebar>
<HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

<style>
:root {
  box-sizing: border-box;
}

* {
  box-sizing: inherit;
}

#app {
  --bg-base: 231, 15%;
  --bg: hsl(var(--bg-base), 18%);
  background: var(--bg);

  font-family: sans-serif;
  color: #f8f8f2;

  display: flex;
}

#app > div {
  padding: 1em;
  flex-grow: 1;
}

#app > * {
  background: var(--bg);
  height: 100vh;
  overflow-y: auto;
  scrollbar-color: #7c7d83 var(--bg);
}
</style>
