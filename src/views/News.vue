<template>
  <div class="news">
  <img alt="Vue logo" src="../assets/logo.png" />
  <br><br>
              <TheNews />
            </div>
        
</template>
<script>
// @ is an alias to /src
import TheNews from "@/components/TheNews.vue";

export default {
  name: "news",
  components: {
    TheNews,
  },
};
</script>
