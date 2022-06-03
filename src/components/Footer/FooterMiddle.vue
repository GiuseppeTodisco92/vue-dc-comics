<template>
  <div class="footer-middle">
      <div class="footer-middle__box container">
        <div class="footer-middle__nav">
          <ul class="footer-middle__nav-style">
            <h1 class="nav-name">dc comics</h1>
            <li><a href="">Characters</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">News</a></li>
            <ul>
              <h1 class="nav-name">shop</h1>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </ul>
          <ul class="footer-middle__nav-style">
            <h1 class="nav-name">dc</h1>
            <li><a href="">Terms of Use</a></li>
            <li><a href="">Privacy plicy(new)</a></li>
            <li><a href="">Ad Choices</a></li>
            <li><a href="">Advertising</a></li>
            <li><a href="">Jobs</a></li>
            <li><a href="">Subscriptions</a></li>
            <li><a href="">Talent Workshops</a></li>
            <li><a href="">CPSC certificates</a></li>
            <li><a href="">Ratings</a></li>
            <li><a href="">Shop Help</a></li>
            <li><a href="">contact US</a></li>
          </ul>
          <ul class="footer-middle__nav-style">
            <h1 class="nav-name">Sites</h1>
            <li><a href="">DC</a></li>
            <li><a href="">MAD Magazine</a></li>
            <li><a href="">DC kids</a></li>
            <li><a href="">DC Universe</a></li>
            <li><a href="">DC Power Visa</a></li>
          </ul>
        </div>
        <div class="footer-middle__logo">
         
        </div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FooterMiddle'
}
</script>

<style lang="scss" scoped>
.footer-middle{
  background-image: url(../../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  &__box{
    display: flex;
    justify-content: space-between;
  }

  &__logo{
    width: 40%;
    padding: 12.5rem 0;
    background-image: url(../../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center ;
   
  }

  &__nav{
    width: 60%;
    display: flex;
    gap: 3.125rem;
    padding: 1.25rem 0;

    .nav-name{
      color: white;
      text-transform: uppercase;
      font-size: 20px;
      padding: .9375rem 0;
      font-weight: bold;
    }

     li{  
          list-style: none;
          padding: .0625rem 0;

          a{
            font-size: 12px;
            text-decoration: none;
            color: #7b7b78;
          }
        }

  }
  
}

</style>