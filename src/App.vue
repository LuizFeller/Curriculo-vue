<script>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import rodape from './components/rodape.vue'

import { RouterLink, RouterView } from 'vue-router'

export default {
    methods: {
        topo () {
            window.scrollTo({top:0, behavior:'smooth'})
        }
    }
}

</script>

<template>


<div class="curriculo">
<header>

  <h1>CURRÍCULO</h1>

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/contact">contact</RouterLink>
        <p></p>
      </nav>
  </header>
</div>

  <main>
  
  <RouterView />
  </main>

<footer>

    <button class="volta-ao-topo" @click="topo()">Voltar ao topo</button>

</footer>

</template>


<style scoped>

header {
  background:blue;
  position: fixed;
  top:0;
  z-index: 2;
  width: 100vw;
  height: 10vh;

  display: flex;

  justify-content: flex-end;
  padding: 4 8rem;
  align-items: center;
}

header nav {
  display: flex;
  justify-content: space-between;

}
h1 {
  position:fixed;
  right: 50%;
  transform: translatex(50%);
}
main {
  padding-top: 10vh;
  min-height: 120vh;
  background: green

}

footer {

  background: rgb(0, 255, 200);
  min-height: 30px;
  text-align: center;

}

.volta-ao-topo {
  background-color: rgb(255, 144, 40);
  font-weight:bold;

  
}

</style>
