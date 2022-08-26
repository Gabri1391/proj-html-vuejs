<template>
  <header>
    <!-- Header top -->
    <div class="container">
        <div class="header-bar d-flex justify-content-between align-items-center">
           <BaseLogo />
            <div class="navbar">
                <ul class="d-flex">
                    <li v-for="item in items" :key="item.id">
                        <figure>
                        <img :src="item.url" :alt="item.text">
                        </figure>
                         {{item.text}}
                    </li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Header bottom -->
    <section class="welcome">
        <div class="welcome-text">
           <div class="title"><i>Friendly Atmosphere</i></div>
           <div class="h1">Welcoming Place</div>
           <div class="subtitle"><i>For Every Child</i></div>
        </div>
        <button>BUY THIS THEME NOW</button>
        <figure>
            <img src="/images/slider_slide2_img1.png" alt="kid">
            <img src="/images/slider_slide2_img2.png" alt="kid">
        </figure>
    </section>
    <section class="beige"></section>
     <div class="banner d-flex justify-content-around align-items-center">
        <div>How to Enroll Your Child into a Class?</div>
        <button class="info-button"> LEARN MORE  <img src="/images/slider_next.png" alt="slider-next"></button>
    </div>
   

  </header>
</template>

<script>
  import  BaseLogo from './BaseLogo.vue'
export default {
  
    name: 'BaseHeader',
     props: {items: Array},
    components:{
        BaseLogo
    }
}
</script>

<style lang="scss" scoped>
  .header-bar{
    height: 120px;

    img{
        width: 180px;
    }

    .navbar{

        margin-top: 30px;

        li{
            padding: 20px;
            color: #554e9e;
            font-size: 1.2rem;

            &:hover{

            background-color: #d2105d;
            }
        }

        figure{
            text-align: center;
            
            img{
                width: 35px;
            }
        }
   

    }
  }

    .welcome{
        background-color: #E3F0FB;
        height: 450px;
        position: relative;

        .welcome-text{
            position: absolute;
            left: 110px;
            top: 150px;

            .title{
                font-size: 2rem;
                color:  #d2105d;
            }

            .h1{
                color: #554e9e;
                font-weight: 700;
                font-size: 3.2rem;
            }

            .subtitle{
                font-size: 3rem;
                color: #554e9e;
            }
        }

        button{
            background-color:  #d2105d;
            color: #fff;
            border: 1px solid  #d2105d;
            width: 200px;
            height: 50px;
            padding: 5px;
            position: absolute;
            left: 110px;
            top: 350px;
            z-index: 1;

            &:hover{
                background-color: #554e9e;
                border: 1px solid #554e9e;
            }
        }

        figure{
            position: absolute;
            right: 100px;
            z-index: 1;
        }

    }
        .beige{
            height: 200px;
            position: relative;
            bottom: 80px;
            background-color: #EAF0E9;
        }

        .banner{
            height: 130px;
            background-color: #554e9e;
            position: relative;
            bottom: 80px;

            div{
                color: #fff;
                font-size: 2.3rem;
            }

            .info-button{
            background-color: #554e9e;
            color: #fff;
            border: 1px solid #fff;
            width: 200px;
            height: 50px;
            padding: 5px;

            &:hover{
            background-color: #fff;
            color: #554e9e;
            }
            }


        }
</style>