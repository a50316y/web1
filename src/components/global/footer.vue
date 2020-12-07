<template lang="pug">
  div
        footer.c-footer.c-footer--light
            div.container
                div.row
                    div.col-lg-6
                        h5.c-footer__title 聯絡資訊
                        ul.c-contact-info
                            li.c-footer__item.c-contact-info__item
                                font-awesome-icon(:icon="['fas', 'map-marker-alt']" class="ItemIcon")  
                                a(class="c-footer__link" href="#!") 台北市信義區信義路一段25號
                            li.c-footer__item.c-contact-info__item
                                font-awesome-icon(:icon="['fas', 'phone']" class="ItemIcon")
                                a(class="c-footer__link" href="#!") 02-2568-1549
                        div.social-btns 
                            a(href="#!" class="icon-btn")
                                font-awesome-icon(:icon="['fab', 'facebook-f']" class="ItemIcon")
                            a(href="#!" class="icon-btn")
                                i(class="fab fa-google-plus-g ItemIcon" aria-hidden="true") 
                            a(href="#!" class="icon-btn")
                                i(class="fab fa-twitter ItemIcon" aria-hidden="true")
                            a(href="#!" class="icon-btn")
                                i(class="fab fa-dribbble ItemIcon" aria-hidden="true")
                            a(href="#!" class="icon-btn")
                                i(class="fab fa-behance ItemIcon" aria-hidden="true")

                    div.col-lg-2
                        h5.c-footer__title 關於
                        ul
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 故事
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 事紀
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 品牌
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 創始
                    div.col-lg-2
                        h5.c-footer__title 服務
                        ul
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 綠化
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 到府
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 流程
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 個人
                    div.col-lg-2
                        h5.c-footer__title 專案
                        ul
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 性質
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 提案
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 流程
                            li.c-footer__item
                                a(class="c-footer__link" href="#!") 風格

                div.c-copyright
                    div.container
                      p.c-copyright___text © 2020 All right reserved

</template>

<script>


export default {
  name: 'Vvfooter',    
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
