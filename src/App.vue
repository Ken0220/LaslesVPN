<template>
  <Navigation/>
  <EasyWithUs/>
  <InfoBox/>
  <Features/>
  <div class="bg-[#F8F8F8] pb-40">
    <ChoosePlan/>
    <Global/>
    <HappyCustom/>
  </div>
  <SubscribeNow class="relative"/>
    <div class="bg-[#EEEFF2] w-full -mt-90 pt-90 sm:-mt-80 sm:pt-80  md:-mt-70 md:pt-70 -z-0">
      <Footer/>
    </div>
</template>

<script setup>
import Navigation from './components/Navigation.vue';
import EasyWithUs from './components/EasyWithUs.vue';
import InfoBox from './components/InfoBox.vue';
import Features from './components/Features.vue';
import ChoosePlan from './components/ChoosePlan.vue';
import Global from './components/Global.vue';
import HappyCustom from './components/HappyCustom.vue';
import SubscribeNow from './components/SubscribeNow.vue';
import Footer from './components/Footer.vue'

</script>
