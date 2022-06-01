<template>
  <div id="app">
    <BaseHeader/>
    <BaseMain/>
    <FooterTop/>
    <FooterMiddle/>
    <FooterBottom/>
  </div>
</template>

<script>
import BaseHeader from './components/Header/BaseHeader.vue'
import BaseMain from './components/Main/BaseMain.vue'
import FooterTop from './components/Footer/FooterTop.vue'
import FooterMiddle from './components/Footer/FooterMiddle.vue'
import FooterBottom from './components/Footer/FooterBottom.vue'

export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    FooterTop,
    FooterMiddle,
    FooterBottom
  }
}
</script>

<style lang="scss">

</style>
