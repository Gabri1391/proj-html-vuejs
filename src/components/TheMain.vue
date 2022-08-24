<template>
  <main>
    <!-- section introduction -->
    <section class="introduction">
        <div class="text-center">Welcome to Fable</div>
        <h5 class="text-center text-secondary mt-3">Fable daycare,preschool and kindergarten</h5>
        <figure>
          <img src="../assets/images/header_divider.png" alt="divider">
        </figure>

    <!-- section rounded card -->
        <ul class="d-flex justify-content-center my-5">
            <li class="flex-column card-description p-3">
                <figure class="odd">
                    <img  class="mt-2" src="../assets/images/schoolbag_alt.png" alt="schoolbag">
                </figure>
                <h3>Morbi etos</h3> 
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta recusandae assumenda aliquid vitae suscipit iusto doloribus nemo laudantium. Mollitia laborum odio quo suscipit id sint illum ullam nemo cumque vero!</p>
            </li>
            <li class="flex-column card-description p-3">
                <figure class="even">
                    <img class="mt-2" src="../assets/images/stroller_alt.png" alt="stroller">
                </figure>
                <h3>Congue Gravida</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta recusandae assumenda aliquid vitae suscipit iusto doloribus nemo laudantium.</p>
            </li>
            <li class="flex-column card-description p-3">
                <figure class="odd">
                    <img class="mt-2" src="../assets/images/globe_alt.png" alt="globe">
                </figure>
                <h3>Praesent Morbi</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </li>
            <li class="flex-column card-description p-3">
                <figure class="even">
                    <img class="mt-2" src="../assets/images/bell_alt.png" alt="bell">
                </figure>
                <h3>Maecenas node</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta recusandae Mollitia laborum odio quo suscipit id sint illum ullam nemo cumque vero!</p>
            </li> 
        </ul>
    </section>

    <!-- section slider -->
    <section class="slider-section">
        <div class="row container ">
            <div class="col-6 pt-5 pb-5">
                <button class="text-white orange">Overview</button>
                <button class="text-secondary">Mission</button>
                <h4 class="pt-3">Our philosopy is learning through play as we offer stimulating environment for children.</h4>
                <div class="d-flex mt-5">
                   <div class="small-rounded orange me-3">
                   <img src="../assets/images/clock_alt.png" alt="clock">
                   </div>
                   <div>
                   <h4>Full day Session</h4>
                   <p class="text-secondary">The staff are very friendly and helpful all the time.</p>
                   </div>
                </div>
                <div class="d-flex mt-5">
                   <div class="small-rounded orange me-3">
                   <img src="../assets/images/clock_alt.png" alt="clock">
                   </div>
                   <div>
                   <h4>Varied Classes</h4>
                   <p class="text-secondary">The place is bigger than it looks from the outside.</p>
                   </div>
                </div>
            </div>
            <!-- Slider -->
            <div class="col-6 pb-5">
                 <div class="mt-5" id="slider">
                    <img class="main-img" src="../assets/images/gallery_08-690x506.jpg" alt="teacher with a kid">
                    <img class="arrow prev" src="../assets/images/slider_previous.png" alt="previous">
                    <img class="arrow next" src="../assets/images/slider_next.png" alt="next">
                 </div>
                 <div id="thumbnails">
                    <img src="../assets/images/gallery_07-690x506.jpg" alt="kids">
                    <img src="../assets/images/gallery_01.jpg" alt="kids">
                    <img src="../assets/images/gallery_08-690x506.jpg" alt="teacher with a kid">
                 </div>
            </div>
        </div>
    </section>
  </main>
</template>

<script>
export default {
    name:'TheMain'

}
</script>

<style lang="scss" scoped>
  div{
    color: #554e9e;
    font-size: 3rem;
  }

  figure{
    text-align: center;
    padding-top: 20px;
  }

  .card-description{
    width: 250px;
  }

  li figure{
    width: 120px;
    height: 120px;
    border-radius: 50%;
  }

h3{
    color: #554e9e;
}

figure.odd{
    background-color: #fe6601;
}

figure.even{
    background-color: #554e9e;
}

.slider-section{
    background-color: #F5F5F5;

    button{
        width: 120px;
        height: 50px;
        padding: 5px;
        font-size: 1.2rem;
        border: #fe6601;
    }

    h4{
        font-size: 1.9rem;
    }

    img{
        margin-left: 22px;
        margin-bottom: 7px;
    }

    .small-rounded{
        width: 80px;
        height: 80px;
        border-radius: 50%;
    }

    .orange{
        background-color: #fe6601;
    }

    p{
        font-size: 1.2rem;
    }
    
    #slider{
        position: relative;

           .main-img{
          width: 570px;
          height: 400px;
        }
    
        .arrow{
            width: 50px;
            height: 50px;
            background-color: #fe6601;
        }

        .prev{
          position: absolute;
          bottom: 180px;
        }
        
        .next{
           position: absolute;
           left: 520px;
           bottom: 180px;

        }
    }

    #thumbnails{
    width: 600px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 30px;
    }

    #thumbnails img{
        width: 30%;
        height: 120px;
    }

    #thumbnails img:hover{
        box-shadow: 0 0  10px #fe6601;
    }
    
}

</style>