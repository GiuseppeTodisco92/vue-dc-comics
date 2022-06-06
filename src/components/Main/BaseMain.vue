<template>
  <main class="main ">
    <hero-section/>
    <card-section/>
      
  </main>
</template>

<script>
import HeroSection from '../sections/HeroSection.vue';
import CardSection from '../sections/CardSection.vue';

export default {
  
    name: 'BaseMain',
    components: { 
      HeroSection, 
      CardSection
       },
}
</script>

<style lang="scss" scoped>


</style>