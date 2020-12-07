<template lang="pug">
    div
      div.jumbotron
        div.mask--light
        div.container
          div.jumbotron__heading 人生放鬆的極致美學
          p.jumbotron__para 現代人生活緊湊，資訊繁多，工作及生活的環境不能馬虎
          p.jumbotron__para 教會你如何放鬆壓力，讓您享受最舒適的生活！
          a(href="#" class="btn btn--primary btn--lg") 點擊了解更多

      div.index-about.hero.hero--white
        div.container
          div.big-word ABOUT
          div.row
            div.col-lg-5
              div.intro
                h3.heading 我們幫助你滿足所需 </br> 提升你家的
                  span.color--secondary 溫度
                p.para 對所有的人來說，有一個安身立命的場所是重要的，不論是在工作、生活、飲食等等，我們的目的在於提供更好的環境。
                a(href="#" class="btn btn--primary btn--md") 關於我們

            div.col-lg-7
              div.img-container
                div(class="image" :style="{backgroundImage: 'url(' + bg + ')' }") 
                //- div(class="image" style="background-image: url('@/assets/img/relax.jpg');") 
                //- div(class="image" style="") 


</template>

<script>
import bg from '../assets/img/natural.jpg'

export default {
  name: 'index',    
  components: {
  },
  data(){
      return{
        bg:bg,
        cssProps: {
          backgroundImage: `url(${require('@/assets/img/natural.jpg')})`
        }        
      }
  }  
}
</script>

<style>
</style>
