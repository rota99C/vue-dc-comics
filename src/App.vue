<template>
  <div id="app">
    <site-header/>
    <image-hero/>
    <site-main/>
    <site-footer/>
    
     
    
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from './components/SiteMain.vue'
import SiteFooter from './components/SiteFooter.vue'
import ImageHero from './components/ImageHero.vue'



export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
    ImageHero
    
  }
}
</script>

<style lang="scss">
 * {
   padding: 0;
   margin: 0;
   box-sizing: border-box;
 }

</style>
