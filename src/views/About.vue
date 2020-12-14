<template>
  <div class="about">
    <img alt="NSC logo" src="../assets/logo.png">
    <br><br>
    <TheServices msg="Servicios de nuestra empresa"/>
  </div>
</template>
<script>
// @ is an alias to /src
import TheServices from '@/components/TheServices.vue'

export default {
  name: 'about',
  components: {
    TheServices
  }
}
</script>
