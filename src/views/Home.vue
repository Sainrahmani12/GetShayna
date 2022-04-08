<template>
  <div class="home">
    <header-shayna/>
    <hero-shayna/>
    <banner/>
    <insta-shayna/>
    <logo-partner/>
    <footer-shayna/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '../components/HeaderShayna.vue'
import HeroShayna from '../components/HeroShayna.vue'
import Banner from '../components/Banner.vue'
import InstaShayna from '../components/InstaShayna.vue'
import LogoPartner from '../components/LogoPartner.vue'
import FooterShayna from '../components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    Banner,
    InstaShayna,
    LogoPartner,
    FooterShayna
}
}
</script>
