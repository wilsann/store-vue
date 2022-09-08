<template>
  <div class="home">

    <HeaderWil />
    <HeroCarousel />
    <WomanSec />
    <InstaSec />
    <PartnerSec />
    <FooterSec />

  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderWil from '@/components/HeaderWil.vue'
import HeroCarousel from '@/components/HeroCarousel.vue'
import WomanSec from '../components/WomanSec.vue'
import InstaSec from '@/components/InstaSec.vue'
import PartnerSec from '../components/PartnerSec.vue'
import FooterSec from '@/components/FooterSec.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderWil,
    HeroCarousel,
    WomanSec,
    InstaSec,
    PartnerSec,
    FooterSec
}
}
</script>
