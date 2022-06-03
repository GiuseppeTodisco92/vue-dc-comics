<template>
  <div class="footer-bottom">
      <div class="footer-bottom__box container">
        <div class="footer-bottom__box-btn">
          <button class="btn-custom">sign-up now!</button>
        </div>
        <div class="footer-bottom__social">
          <h1 class="follow">follow us</h1>
          <a href=""><img src="../../assets/img/footer-facebook.png" alt=""></a>
          <a href=""><img src="../../assets/img/footer-twitter.png" alt=""></a>
          <a href=""><img src="../../assets/img/footer-youtube.png" alt=""></a>
          <a href=""><img src="../../assets/img/footer-pinterest.png" alt=""></a>
          <a href=""><img src="../../assets/img/footer-periscope.png" alt=""></a>
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FooterBottom'
}
</script>

<style lang="scss" scoped>
.footer-bottom{
  padding: 72px 0;
  background-color: var(--secondary-color);

  .btn-custom{
    text-transform: uppercase;
    color: white;
    font-size: 1.125rem;
    border: 2px solid var(--primary-color);
    padding: .9375rem 1.5625rem;
    background-color: transparent;
  }

  &__box{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  &__social{
    display: flex;
    align-items: center;
    gap: 1.25rem;

    .follow{
      color: var(--primary-color) ;
      text-transform: uppercase;
      font-size: 25px;
    }
  }
}
</style>