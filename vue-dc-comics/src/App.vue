<template>
  <div id="app">
    <site-header/>
    <site-main/>
    <site-footer/>
    
     
    
  </div>
</template>

<script>
import SiteHeader from './components/SiteHeader.vue'
import SiteMain from './components/SiteMain.vue'
import SiteFooter from './components/SiteFooter.vue'


export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter
    
  }
}
</script>

<style lang="scss">

</style>
