<template>
  <h1>Camisas Belligham</h1>
  <br>
  <div class="container">
    <div class="row">
      <div class="col-sm-3">
        <div class="mb-4">
          <div class="card" style="width: 18rem;">
            <img src="../assets/img/1.png" class="card-img-top" width="250px" height="250px">
            <div class="card-body">
              <h5 class="card-title">Camisa inglaterra</h5>
              <p class="card-text">Camisas exclusivas solo aqui,en Hala madrid</p>
              <a href="https://www.realmadrid.com/" class="btn btn-primary">Visitanos para mas informacion</a>
            </div>
          </div>
        </div>
        <div class="mb-4">
          <div class="card" style="width: 18rem;">
            <img src="../assets/img/2.png" class="card-img-top" width="250px" height="250px">
            <div class="card-body">
              <h5 class="card-title">Camisa Dormund</h5>
              <p class="card-text">Camisas exclusivas aqui, en hala madrid</p>
              <a href="#" class="btn btn-primary">Visitanos para mas informacion</a>
            </div>
          </div>
        </div>
        <div class="mb-4">
          <div class="card" style="width: 18rem;">
            <img src="../assets/img/3.png" class="card-img-top" width="250px" height="250px">
            <div class="card-body">
              <h5 class="card-title">Camisa madrid</h5>
              <p class="card-text">Camisa exclusiva solo aqui, en hala madrid</p>
              <a href="#" class="btn btn-primary">Visitanos para mas informacion</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

  <script lang="ts">
    import { defineComponent } from 'vue';
    import posts from '@/assets/posts.json'
    export default defineComponent({
      name: 'CamisasBelligham'
      
    })

  </script>

  <style lang="scss" scoped>
  .contenedor-flex {
  display: flex;
  justify-content: center; /* Centra horizontalmente */
  align-items: center; /* Centra verticalmente */
  height: 100vh; /* Ajusta la altura según tus necesidades */
}

  </style>