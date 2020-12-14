<template>
  <div class="team">
    <img alt="NSC logo" src="../assets/logo.png">
    <br><br>
    <div class="container">
      <div class="row">
        <div class="col-3">
          
          <TeamCard 
          imagen="https://i.postimg.cc/sXMGJSGK/Omar.jpg"
          nombre="Omar Rodríguez"
          edad="45 años" 
          rol="Tester" 
          descripcion="Ingeniero Químico graduado de la Universidad Nacional de Colombia, dentro de sus pasatiempos favoritos están: el cine y ciclismo"  />
        </div>
        <div class="col-3">
          
          <TeamCard
          imagen="https://i.postimg.cc/0rRkDK76/Juan-Moreno.jpg"
          nombre="Juan  Moreno" 
          edad="39 años" 
          rol="Backend" 
          descripcion="Ingeniero electrónico de la Universidad Nacional de Colombia, dentro de sus pasatiempos están: Leer y  jugar juegos de mesa"  />
        </div>
        <div class="col-3">
          
          <TeamCard
          imagen= "https://i.postimg.cc/wTm3MgDy/Juan-Yepes.jpg"
          nombre="Juan Yepes" 
          edad="42 años" 
          rol="Arq Software" 
          descripcion="Médico de la Universidad de Antioquia, dentro de sus pasatiempos favoritos esta disfrutar del Cine y las nuevas tecnologías"  />
        </div>
        <div class="col-3">
          
          <TeamCard 
          imagen= "https://i.postimg.cc/FKtyzTfm/diana.jpg"
          nombre="Diana Moreno" 
          edad="25 años" 
          rol="Frontend" 
          descripcion="Diseñadora Industrial graduada de la UPTC, dentro de sus pasatiempos favoritos están: Leer y hacer ejercicio"  />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import TeamCard from "@/components/TeamCard.vue";

export default {
  name: "Team",
  components: {
    TeamCard ,
  },
};
</script>