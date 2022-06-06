<template>
   
  <header class="header container">
      <div class="header__logo_box">
          <img class="header__logo_img"  src="../../assets/img/dc-logo.png" alt="dc-logo"> 
      </div>
     
     <ul class="header__nav">
         <li v-for="(link,index) in links" :key="index" :class="{active : link.current}" ><a href="link.url">{{link.text}}</a></li>
         
     </ul>
  </header>
</template>

<script>
 
export default {
    name: 'BaseHeader',
    // inserire i data dei link
    data(){
        return {
            links: [
                {
                    text:"characters",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"comics",
                    ulr:"#",
                    current: true,
                },
                {
                    text:"movies",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"tv",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"games",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"collectibles",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"videos",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"fans",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"news",
                    ulr:"#",
                    current: false,
                },
                {
                    text:"shop",
                    ulr:"#",
                    current: false,
                },

                

            ],
        }
    } 
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
        flex-wrap: wrap;
        align-items: center;

         a{
        text-decoration: none;
        color: black;
        text-transform: uppercase;
        font-size: .75rem;
        font-weight: bolder;
        
        }

        .active { // header__nav ul .active a
               color: var(--primary-color);
               border-bottom: 4px solid var(--primary-color) ;
               margin-top:5px;
               padding: 50px 0px;
        }

        a:hover{
            color: var(--primary-color);
        }

    }

   

}

</style>