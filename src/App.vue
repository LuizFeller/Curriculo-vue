<script>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'

import { RouterLink, RouterView } from 'vue-router'
</script>

<template>

  <div class="curriculo">
  <header>
    <h1>CURRÍCULO</h1>
  </header>
</div>

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/contact">contact</RouterLink>
        <p>Teste</p>
      </nav>
  </header>

  <main>
    
    
  <RouterView />
  </main>

<footer>meu rodapé </footer>
</div>


</template>

<style scoped>

header {
  background:white;
  position: fixed;
  top:0;
  z-index: 2;
  width: 100vw;
  height: 10vh;

  display: flex;

  justify-content: space-between;
  padding: 0 2rem;
  align-items: center;
}

header nav {
  display: flex;
  justify-content: space-between;
}

main {
  padding-top: 10vh;
  min-height: 120vh;
  background: green

}

footer {

  background: red

}

</style>
