<template>
  <footer class="footer">
    <div class="footer__container">
      <div class="footer__row">
        <div class="footer__useful-links useful-links">
          <h4 class="useful-links__title">لینک های مفید</h4>
          <ul class="useful-links__items">
            <li class="useful-links__item" v-for="(link,index) in links" :key="index"><a :href="link.url" target="_blank" class="useful-links__link">{{link.text}}</a></li>
          </ul>
        </div>
        <div class="footer__about-us about-us">
          <h4 class="about-us__title">ارتباط با ما</h4>
          <p class="about-us__item item" v-for="(contact,index) in contacts" :key="index">
           <span class="item__title">{{contact.title}} : </span> 
           <span class="item__content">{{contact.content}}</span>
          </p>          
        </div>
        <div class="footer__social social">
          <h4 class="social__title">شبکه های اجتماعی</h4>
          <div class="social__items">
            <a :href="social.imgUrl" class="social__link" v-for="(social,index) in socials" :key="index"><img :src="social.imgSrc" alt="" class="social__img social--instagram"></a>
          </div>
        </div>
      </div>
    </div>
    <p class="footer__copyright">{{copyright +'@' + copyrightDate}}</p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
   data() {
    return {
      copyright: '© تمامی حقوق برای عصر ویرا محفوظ است',
      copyrightDate: 2020,

      socials:[
        {
          imgUrl: 'instagram.com',
          imgSrc: 'src/assets/img/social/instagram.png'
        },
        {
          imgUrl: 'telegram.com',
          imgSrc: 'src/assets/img/social/telegram.png'
        },
        {
          imgUrl: 'twitter.com',
          imgSrc: 'src/assets/img/social/twitter.png'
        },
        {
          imgUrl: 'aparat.com',
          imgSrc: 'src/assets/img/social/aparat.png'
        },
        {
          imgUrl: 'instagram.com',
          imgSrc: 'src/assets/img/social/instagram.png'
        },
        {
          imgUrl: 'facebook.com',
          imgSrc: 'https://picsum.photos/id/237/200/300'
        },
        {
          imgUrl: 'facebook.com',
          imgSrc: 'https://picsum.photos/id/237/200/300'
        },
        {
          imgUrl: 'facebook.com',
          imgSrc: 'https://picsum.photos/id/237/200/300'
        },
        {
          imgUrl: 'facebook.com',
          imgSrc: 'src/assets/img/social/facebook.png'
        },
      ]
      ,
      links:[
        {
          text: 'سوالات',
          url: 'www.amir.ir'
        },
        {
          text: 'سوالات',
          url: 'www.amir.ir'
        },
        {
          text: 'سوالات',
          url: 'www.amir.ir'
        },
        {
          text: 'سوالات',
          url: 'www.amir.ir'
        },
        {
          text: 'سوالات',
          url: 'www.amir.ir'
        },
        {
          text: 'سوالات',
          url: 'www.amir.ir'
        },
      ],
      contacts:[
        {
          title: 'تلفن شرکت',
          content: '02188776655'
        },
        {
          title: 'تلفن شرکت',
          content: '02188776655'
        },
        {
          title: 'تلفن شرکت',
          content: '02188776655'
        },
        {
          title: 'تلفن شرکت',
          content: '02188776655'
        },
      ]
    }
   }
}
</script>

<style>

</style>