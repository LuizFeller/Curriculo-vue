<script>
import TheWelcome from '../components/TheWelcome.vue'
import foto from '@/assets/foto.svg'

export default{
  data(){
    return{
      foto
    }
  }
}



</script>

<template>
  <div class="main">

    <section>
      <h2>LUIZ ALFREDO FELLER</h2>
      
      <div class="container-img center">
          <img :src="foto" width="100" alt="">
      </div>

    </section>
  </div>

</template>

<style scoped>

div.main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding-left: 0rem;
  margin-top: 50%;

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
