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
  <header>
    <div >
        <nav class="divCabecalho">
          <router-link to="/" tag="button" class="btn btn-primary btn-lg espacoEntreBotoes">Apresentação</router-link>
          <router-link to="/about" tag="button" class="btn btn-primary btn-lg espacoEntreBotoes">Currículo</router-link>
          <router-link to="/galeria" tag="button" class="btn btn-primary btn-lg espacoEntreBotoes">Galeria</router-link> 
        </nav>
      </div>
  </header>
  <main>
    <div class="area">
      <ul class="circles">
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
      </ul>
      <div class="divCabecalho"></div>
    <RouterView />
  </div>
</main>
<footer class="area">
  <button type="button" class="btn btn-primary btn-lg" @click="topo()"><i class="bi bi-arrow-bar-up"></i>Voltar ao topo</button>
</footer>
</template>
<style>
</style>