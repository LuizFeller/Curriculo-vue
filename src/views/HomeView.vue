<script>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <div class="main">

    <section>
      <h2>LUIZ ALFREDO FELLER</h2>
      

    </section>
  </div>
      <div class="foto">
          <img src="../Fotos/Foto.jpeg" width="320" height="400" alt="">
      </div>

</template>

<style scoped>


.foto {
  justify-content: center;
  text-align: center;
  width: center;

}

div.main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding-left: 0rem;
  margin-top: 10%;

}

section {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  text-align: left;
  margin: 50px;
  max-width: 1000px;
  /*background-color: aqua;*/
}

/*div.main2 {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding-left: 20rem;*/



section {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  text-align: left;
}
</style>
