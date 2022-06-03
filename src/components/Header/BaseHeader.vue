<template>
   
  <header class="header container">
      <div class="header__logo_box">
          <img class="header__logo_img"  src="../../assets/img/dc-logo.png" alt="dc-logo"> 
      </div>
     
     <ul class="header__nav">
         <li><a href="">characters</a></li>
         <li><a class="active" href="">comics</a></li>
         <li><a href="">movies</a></li>
         <li><a href="">tv</a></li>
         <li><a href="">games</a></li>
         <li><a href="">collectibles</a></li>
         <li><a href="">videos</a></li>
         <li><a href="">fans</a></li>
         <li><a href="">news</a></li>
         <li><a href="">shop</a></li>
     </ul>
  </header>
</template>

<script>
 
export default {
    name: 'BaseHeader',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/mixins.scss';
.header{
    display: flex;
    justify-content: space-between;

    &__logo_box{
        margin: 1.125rem  0;
        display: flex;
        align-items: center;
    }

    &__logo_img{
        width: 80px;
    }

    

    &__nav{
        @include listInline;
        display: flex;
        align-items: center;

         a{
        text-decoration: none;
        color: black;
        text-transform: uppercase;
        font-size: .75rem;
        font-weight: bolder;
        padding: 45px 0px;
        }

        .active { // header__nav ul .active a
               color: var(--primary-color);
               border-bottom: 5px solid var(--primary-color) ;
        }

        a:hover{
            color: var(--primary-color);
        }

    }

   

}

</style>