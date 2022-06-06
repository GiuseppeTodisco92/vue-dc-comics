<template>
  <div class="footer-top">
      <ul class="footer-top__nav">
        <li><a href="#"><img src="../../assets/img/buy-comics-digital-comics.png" alt=""> digital comics</a></li>
        <li><a href="#"><img src="../../assets/img/buy-comics-merchandise.png" alt=""> dc merchandise</a></li>
        <li><a href="#"><img src="../../assets/img/buy-comics-subscriptions.png" alt=""> subscription</a></li>
        <li><a href="#"><img src="../../assets/img/buy-comics-shop-locator.png" alt=""> comic shop locator</a></li>
        <li><a href="#"><img src="../../assets/img/buy-dc-power-visa.svg" alt=""> dc power visa</a></li>
      </ul>
  </div>
</template>

<script>
export default {
    name: 'FooterTop'
}
</script>

<style lang="scss" scoped>

@import '../../assets/style/mixins.scss';
.footer-top{
  padding: 50px 0;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--primary-color);
    
  &__nav{
    @include listInline;
    display: flex;
    flex-wrap: wrap;
    gap: 3.75rem;

    a{
      display: flex;
      align-items: center;
      gap: 1.25rem;
      color: white;
      text-decoration: none;
      text-transform: uppercase;
      font-size: .75rem;
    }
  }

  img{
    width: 35px;
  }
 
}




</style>