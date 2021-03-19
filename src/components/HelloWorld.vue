<template>
  <div class="app-container">

    <div class="welcome-mjs-container">
      <p CLass="welcome-msj"> Hi <b>Guz</b>!</p>
    </div>

    <div class="food-promotion-container">
      <div class="food-title">
        Hamburguesa + Papas fritas
      </div>
      <div class="food-description">
        El combo mas conveniente para tu dia
      </div>
      <div class="food-img-container">
        <img class="food-img" src="https://image.freepik.com/foto-gratis/manzana-roja-aislada_74190-1286.jpg" alt="Manzana.png">
      </div>
    </div>

    <div class="category-roll">
      <div class="category-product">
        <div class="product-icon">
          <i class="bi bi-cup-straw"></i>
        </div>
        <div class="product-name"> Hamburguesa </div>
      </div>
    </div>

    <div class="top-products-container-roll">
      <p class="top-products-title"> Top Productos</p>
      <div class="top-product">
        <div class="top-img">
        </div>
        <div class="top-name">
        </div>
        <div class="top-price"></div>
        <div class="top-add-icon">
          <i class="bi bi-plus-circle-fill"></i>
        </div>
      </div>
    </div>

    <div class="menu-bottom-container">
      <div class="menu-bottom">
        <a class="nav-icon">
         <i class="bi bi-house"></i>
        </a>
       <a class="nav-icon">
          <i class="bi bi-bag-check"></i>
       </a>
       <a class="nav-icon">
         <i class="bi bi-heart"></i>
       </a>
       <a class="nav-icon">
         <i class="bi bi-clock-history"></i>
       </a>


      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.welcome-msj{
  text-align: left;
  margin: 10px;
  padding: 10px;
  font-size: 30px;
}
.menu-bottom-container{

}
.menu-bottom{
  width: 100%;
  align-content: center;
  display: flex;
  justify-content: space-between;
  position: fixed;
  bottom: 0;
  padding: 20px;
}
.nav-icon{

}
.food-img{
  width: 50px;
}




.top-products-title{
  font-size: 20px;
  text-align: left;
  margin: 10px;
  padding: 10px;
}
</style>
