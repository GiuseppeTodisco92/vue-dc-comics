<template>
  <main class="main ">
    <hero-section/>
      
  </main>
</template>

<script>
import HeroSection from '../sections/HeroSection.vue'

export default {
  components: { HeroSection },
    name: 'BaseMain'
}
</script>

<style lang="scss" scoped>
  .main{
    color: white;
    background-color: black;
    display: flex;
    align-items: center;
  }


</style>