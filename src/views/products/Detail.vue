<template>
  <div class="container">
    <div class="cover">
      <div class="col-md-12">
        <h3 class="text-center">Product Detail</h3>
      </div>
      <div class="row">
        <div class="col-md-2">
        </div>
        <div class="col-md-8">
          <div class="col-md-12 img-section">
            <img src="https://placehold.it/800x600/000" alt="">
          </div>
          <div class="col-md-12">
            <h4>Product Title {{ id }} </h4>
            <p>Product Description</p>
            <a href="#" class="btn btn-success btn-sm">Agregar</a>
          </div>
        </div>        
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        id: this.$route.params.id 
      }
    }
  }
</script>

<style>

  .cover{
    padding: 20px;
    margin: 40px 2px;
    border: 1px solid #d2e0e6;
  }

  .img-section img{
    width: 100%;
  }

</style>