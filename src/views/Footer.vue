<template>
  <footer class="footer">
    <div class="footer__container">
      <div class="footer__row">
        <div class="footer__useful-links useful-links">
          <h4 class="useful-links__title">لینک های مفید</h4>
          <ul class="useful-links__items">
            <li class="useful-links__item"><a href="" class="useful-links__link">asd</a></li>
            <li class="useful-links__item"><a href="" class="useful-links__link">asd</a></li>
            <li class="useful-links__item"><a href="" class="useful-links__link">asd</a></li>
            <li class="useful-links__item"><a href="" class="useful-links__link">asd</a></li>
            <li class="useful-links__item"><a href="" class="useful-links__link">asd</a></li>
          </ul>
        </div>
        <div class="footer__about-us about-us">
          <h4 class="about-us__title">ارتباط با ما</h4>
          <p class="about-us__item item">
           <span class="item__title">تلفن شرکت : </span> 
           <span class="item__content">0218421844</span>
          </p>          
          <p class="about-us__item item">
           <span class="item__title">تلفن شرکت : </span> 
           <span class="item__content">0218421844</span>
          </p>          
          <p class="about-us__item item">
           <span class="item__title">تلفن شرکت : </span> 
           <span class="item__content">0218421844</span>
          </p>
        </div>
        <div class="footer__social social">
          <h4 class="social__title">شبکه های اجتماعی</h4>
          <div class="social__items">
            <a href="" class="social__link"><img src="@/assets/img/social/instagram.png" alt="" class="social__img social--instagram"></a>
            <a href="" class="social__link"><img src="@/assets/img/social/telegram.png"  alt="" class="social__img social--telegram"></a>
            <a href="" class="social__link"><img src="@/assets/img/social/twitter.png"   alt="" class="social__img social--twitter"></a>
            <a href="" class="social__link"><img src="@/assets/img/social/aparat.png"    alt="" class="social__img social--youtube"></a>
            <a href="" class="social__link"><img src="@/assets/img/social/aparat.png"    alt="" class="social__img social--aparat"></a>
            <a href="" class="social__link"><img src="@/assets/img/social/facebook.png"  alt="" class="social__img social--facebook"></a>
          </div>
        </div>
      </div>
    </div>
    <p class="footer__copyright">{{copyright}}</p>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
   data() {
    return {
      copyright: '© تمامی حقوق برای عصر ویرا محفوظ است',
      
    }
   }
}
</script>

<style>

</style>