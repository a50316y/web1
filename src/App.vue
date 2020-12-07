<template lang="pug">
  div.app
    Vvheader
    section.main
      router-view
    Vvfooter  

</template>

<script>
import Vvheader from "@/components/global/header.vue";
import Vvfooter from "@/components/global/footer.vue";

export default {
  name: 'App',
  components: {
    Vvheader,
    Vvfooter
  }  
}
</script>

<style>

</style>
