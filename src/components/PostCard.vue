<template>
    <div class="card" style="width: 18rem;">
            <img src="../assets/img/1.png" class="card-img-top" width="250px" height="250px">
            <div class="card-body">
              <h5 class="card-title">Camisa inglaterra</h5>
              <p class="card-text">Camisas exclusivas solo aqui,en Hala madrid</p>
              <post-button/>
            </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import PostButton from './PostButton.vue';
export default defineComponent({
    name: "PostCard",
    components:{
        PostButton
    }
})

</script>

<style lang="scss">

</style>