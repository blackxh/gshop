<template>
  <div>
    <router-view/>
    <FooterGuide v-show="$route.meta.showFooter"/>
  </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide'

  export default {
    components: {
      FooterGuide
    },
    data () {
      return {

      }
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  
</style>






