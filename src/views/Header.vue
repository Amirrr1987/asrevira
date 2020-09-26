<template>
  <header class="header">
    <Navbar class="header__navbar"/>
    <div class="header__content">
      <h1 class="header__title">عصر ویرا</h1>
      <h2 class="header__slogan">تجربه ی عصر هوشمند</h2>
      <a to="/login" class="header__login">ورود عضویت</a>
    </div>
    <img src="@/assets/img/header/Flag.png" title="" alt="" class="header__flag">
  </header>
</template>

<script>
import Navbar  from '@/components/Navbar';
export default {
  name: 'Header',
  components:{
    Navbar,
  }
}
</script>

<style>

</style>