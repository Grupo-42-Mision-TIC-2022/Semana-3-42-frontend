<template>
  <div class="contactus">
    <img alt="NSC logo" src="../assets/logo.png">
    <br><br>
    <ContactUs msg="Contáctanos"/>
  </div>
</template>

<script>
// @ is an alias to /src
import ContactUs from '@/components/ContactUs.vue'

export default {
  name: 'Contactus',
  components: {
    ContactUs
  }
}
</script>
