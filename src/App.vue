<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a href=""> <img src="../public/img2/logo.png" alt=""></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="../src/components/CamisasBelligham.vue">Camisas Belligham</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="../src/components/CamisasVini">Camisas Vinicius jr</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="../src/components/CamisasModric.vue">Camisas Luka Modrid</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';

import CamisasBelligham from './components/CamisasBelligham.vue'

import CamisasModric from './components/CamisasModric.vue'

import CamisasVini from './components/CamisasVini.vue'

export default defineComponent({
  components: {
    CamisasBelligham
    CamisasModric
    CamisasVini
  }
})



</script>

<style lang="ts" scoped>



</style>
