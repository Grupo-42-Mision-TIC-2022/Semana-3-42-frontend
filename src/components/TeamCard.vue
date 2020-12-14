<template>
  <div class="teamcard">
    <div class="card" style="width: 14rem">
        <div class="card-body">
          <img :src=imagen class="card-img-top" style="width: 12rem"  alt="..."  />
        <h5 class="card-title">{{nombre}},{{edad}}, {{rol}}</h5>
        <p class="card-text">
          {{descripcion}}
        </p>
        <a href="#" class="btn btn-success">Regresar al Menú</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TeamCard",
  props: {
    imagen: String,
    nombre: String,
    edad: Number,
    rol: String,
    descripcion: String
      }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
