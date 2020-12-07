<template lang="pug">
  div
    header.header
      div.c-navbar.c-navbar--light
        div.container-fluid
          div.c-navbar__inner
            a(href="#" class="c-navbar__logo")
            ul.c-nav.c-navbar__nav
              li.c-nav__item
                a(href="#!" class="c-nav__link") 首頁
              li.c-nav__item
                a(href="#!" class="c-nav__link") 關於
              li.c-nav__item
                a(href="#!" class="c-nav__link") 服務
              li.c-nav__item
                a(href="#!" class="c-nav__link") 專案
              li.c-nav__item
                a(href="#!" class="c-nav__link") 聯絡

</template>

<script>


export default {
  name: 'Vvheader',    
  components: {
  },
  data(){
      return{
      }
  }  
}
</script>

<style>
</style>
