<script>

export default {
  components:{
  }
}
</script> 

<template>
  <div class="titulo">
      <h2>LUIZ ALFREDO FELLER</h2>
  </div>
  <div id="carouselExample" class="carousel slide">
  <div class="carousel-inner foto">
    <div class="carousel-item active">
      <img src="@/assets/galeria1.png" height="500">
    </div>
    <div class="carousel-item foto">
      <img src="@/assets/galeria2.png" height="500">
    </div>
    <div class="carousel-item foto">
      <img src="@/assets/galeria3.png" height="500">
    </div>
    <div class="carousel-item foto">
      <img src="@/assets/galeria4.png" height="500">
    </div>    
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>  
</template>
<style>
</style>