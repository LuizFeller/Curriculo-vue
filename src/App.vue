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
        <RouterLink to="/">Capa</RouterLink>
        <RouterLink to="/about">Conteúdo</RouterLink>
        <RouterLink to="/contact">Final</RouterLink>

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
  width: 30%;

}
/* ajustes de posicionamento de Home, About and Contact*/
nav a {
color:black;
top: -35px;
right: 120%;

}

h1 {
  position:fixed;
  right: 50%;
  transform: translatex(50%);
}
main {
  padding-top: 10vh;
  min-height: 120vh;
  background:gray;

}

footer {

  /* background: rgb(0, 255, 200); */
  background: blue;
  min-height: 40px;
  text-align: center;

}

.volta-ao-topo {
  background-color: rgb(255, 187, 40);
  font-weight:bold;

  
}

</style>
