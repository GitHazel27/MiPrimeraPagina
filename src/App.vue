<script setup lang="ts">
import {ref} from 'vue'
import Header from './components/Header.vue'
/*import HelloWorld from './components/HelloWorld.vue'*/
import Body from './components/Body.vue'
/*import TheWelcome from './components/TheWelcome.vue'*/
</script>

<template>
  <Header></Header>

  <Body></Body>
</template>

<style scoped>
.hero {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  .hero {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  .hero .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
