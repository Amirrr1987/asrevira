<template>
  <main class="main landing">
      <LandingInfo/>
      <LandingNews/>
      <LandingServices/>
      <LandingTraining/>
  </main>
</template>

<script>
import LandingInfo     from '@/components/LandingInfo';
import LandingNews     from '@/components/LandingNews';
import LandingServices from '@/components/LandingServices';
import LandingTraining from '@/components/LandingTraining';
export default {
    name: 'Landing',
    components:{
      LandingInfo,
      LandingNews,
      LandingServices,
      LandingTraining,

    }
}
</script>

<style>

</style>