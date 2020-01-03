<template>
  <div class="container">
    <div class="cover">
      <div class="col-md-12">
        <h3>Products</h3>
      </div>
      <div class="row">
        <div class="col-md-3">
          <div class="col-md-12">
            <img src="https://placehold.it/200x100/000" alt="">
          </div>
          <div class="col-md-12">
            <h4>Product Title 1</h4>
            <p>Product Description</p>
            <router-link :to="{ name: 'product-detail', params: { id: 1 } }" class="btn btn-success btn-sm"> Ver detalle </router-link>
          </div>
        </div>

        <div class="col-md-3">
          <div class="col-md-12">
            <img src="https://placehold.it/200x100/000" alt="">
          </div>
          <div class="col-md-12">
            <h4>Product Title 2</h4>
            <p>Product Description</p>
            <router-link :to="{ name: 'product-detail', params: { id: 2 } }" class="btn btn-success btn-sm"> Ver detalle </router-link>
          </div>
        </div>

        <div class="col-md-3">
          <div class="col-md-12">
            <img src="https://placehold.it/200x100/000" alt="">
          </div>
          <div class="col-md-12">
            <h4>Product Title 3</h4>
            <p>Product Description</p>
            <router-link :to="{ name: 'product-detail', params: { id: 3 } }" class="btn btn-success btn-sm"> Ver detalle </router-link>
          </div>
        </div>

        <div class="col-md-3">
          <div class="col-md-12">
            <img src="https://placehold.it/200x100/000" alt="">
          </div>
          <div class="col-md-12">
            <h4>Product Title 4</h4>
            <p>Product Description</p>
            <router-link :to="{ name: 'product-detail', params: { id: 4 } }" class="btn btn-success btn-sm"> Ver detalle </router-link>
          </div>
        </div>

        
      </div>
    </div>
  </div>
</template>

<style>

  .cover{
    padding: 20px;
    margin: 40px 2px;
    border: 1px solid #d2e0e6;
  }

</style>