<template>
  <main>
    <!-- section introduction -->
    <section class="introduction">
        <div class="title text-center">Welcome to Fable</div>
        <h5 class="text-center text-secondary mt-3">Fable daycare,preschool and kindergarten</h5>
        <figure>
          <img src="/images/header_divider.png" alt="divider">
        </figure>

    <!-- section rounded card -->
        <ul class="d-flex justify-content-center my-5">
            <li class="flex-column card-description p-3">
                <figure class="odd">
                    <img  class="mt-2" src="/images/schoolbag_alt.png" alt="schoolbag">
                </figure>
                <h3>Morbi etos</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta recusandae assumenda aliquid vitae suscipit iusto doloribus nemo laudantium. Mollitia laborum odio quo suscipit id sint illum ullam nemo cumque vero!</p>
            </li>
            <li class="flex-column card-description p-3">
                <figure class="even">
                    <img class="mt-2" src="/images/stroller_alt.png" alt="stroller">
                </figure>
                <h3>Congue Gravida</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta recusandae assumenda aliquid vitae suscipit iusto doloribus nemo laudantium.</p>
            </li>
            <li class="flex-column card-description p-3">
                <figure class="odd">
                    <img class="mt-2" src="/images/globe_alt.png" alt="globe">
                </figure>
                <h3>Praesent Morbi</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
            </li>
            <li class="flex-column card-description p-3">
                <figure class="even">
                    <img class="mt-2" src="/images/bell_alt.png" alt="bell">
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
                <h4 class="pt-3 title">Our philosopy is learning through play as we offer stimulating environment for children.</h4>
                <div class="d-flex mt-5">
                   <div class="small-rounded orange me-3">
                        <img class="mt-4" src="/images/clock_alt.png" alt="clock">
                   </div>
                   <div>
                   <h4 class="title">Full day Session</h4>
                   <p class="text-secondary">The staff are very friendly and helpful all the time.</p>
                   </div>
                </div>
                <div class="d-flex mt-5">
                   <div class="small-rounded orange me-3">
                        <img class="mt-4" src="/images/clock_alt.png" alt="clock">
                   </div>
                   <div>
                   <h4 class="title">Varied Classes</h4>
                   <p class="text-secondary">The place is bigger than it looks from the outside.</p>
                   </div>
                </div>
            </div>
            <!-- Slider -->
            <div class="col-6 pb-5">
                 <div class="mt-5" id="slider">
                    <img class="main-img" src="/images/gallery_08-690x506.jpg" alt="teacher with a kid">
                    <img class="arrow prev" src="/images/slider_previous.png" alt="previous">
                    <img class="arrow next" src="/images/slider_next.png" alt="next">
                 </div>
                 <div id="thumbnails">
                    <img src="/images/gallery_07-690x506.jpg" alt="kids">
                    <img src="/images/gallery_01.jpg" alt="kids">
                    <img src="/images/gallery_08-690x506.jpg" alt="teacher with a kid">
                 </div>
            </div>
        </div>
    </section>
    <!-- Cards section -->
    <section class="cards-sections container pb-5">
        <div class="title text-center mt-5">Our Classes</div>
        <h5 class="text-center text-secondary mt-3">Our preschool programm has four dedicated classes</h5>
        <figure>
          <img src="/images/header_divider.png" alt="divider">
        </figure>

        <div class="row ">
            <div class="col-6">
                <h3 class="pt-5">We provived four classes from nine to twenty childrent each aged from twelve month to five years of age. </h3>
                <div class="d-flex flex-row mt-5">
                    <div class="bg-warning w-50 h-50">
                        <div class="text-white fs-3 ps-3 pt-3">Little Lamb</div>
                        <div class="text-secondary fs-6 ps-3 pb-5">Class Name</div>
                        <div class=" d-flex pt-2">
                            <div class="ps-3 pe-5 pt-1 text-white">12-24 <br> Months old </div>
                            <div class="ps-6 text-white pt-1">9 <br> Class size</div>
                        </div>
                    </div>
                   <img class="img-fluid w-50 h-50" src="/images/gallery_04-690x506.jpg" alt="">
                </div>

                 <div class="d-flex flex-row mt-5">
                    <div class="w-50 h-50 bg-warning">
                        <div class="text-white fs-3 ps-3 pt-3">Tenderhearts</div>
                        <div class="text-secondary fs-6 ps-3 pb-5">Class Name</div>
                        <div class=" d-flex pt-2">
                            <div class="ps-3 pe-5 text-white pt-1">3-4 <br> Years old </div>
                            <div class="ps-6 text-white pt-1">9 <br> Class size</div>
                        </div>
                    </div>
                   <img class="img-fluid w-50 h-50" src="/images/class_03-690x506.jpg" alt="">
                </div>
            </div>
            <div class="col-6">
                <div class="text-secondary fs-6 pt-5">Praesent arcu gravida vehicula est node maecenas loareet morbi a dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis facilisis venenatis. Aenean interdum, nibh vitae sodales, magna ante feugiat elit maecenas.Gravida vehicula est node maecenas loareet morbi.</div>
                 <div class="d-flex flex-row mt-5">
                    <div class="bg-warning w-50 h-50">
                        <div class="text-white fs-3 ps-3 pt-3">Bouncy Bears</div>
                        <div class="text-secondary fs-6 ps-3 pb-5">Class Name</div>
                        <div class=" d-flex pt-2">
                            <div class="ps-3 pe-5 text-white pt-1">2-3 <br> Years old </div>
                            <div class="ps-6 text-white pt-1">9 <br> Class size</div>
                        </div>
                    </div>
                   <img class="img-fluid w-50 h-50" src="/images/class_02-690x506.jpg" alt="">
                </div>

                 <div class="d-flex flex-row mt-5">
                    <div class="bg-warning w-50 h-50">
                        <div class="text-white fs-3 ps-3 pt-3">Shining Stars</div>
                        <div class="text-secondary fs-6 ps-3 pb-5">Class Name</div>
                        <div class=" d-flex pt-2">
                            <div class="ps-3 pe-5 text-white">4-5 <br> Years old </div>
                            <div class="ps-6 text-white">20 <br> Class size</div>
                        </div>
                    </div>
                   <img class="img-fluid w-50 h-50" src="/images/class_04-690x506.jpg" alt="">
                </div>
            </div>
        </div>
    </section>
    <!-- Skills section -->
    <section class="skills bg-light pb-5">
        <div class="row container">
           <div class="col-6">
               <h3 class="pt-5">We have been educating children for over fifteen years. Our goal is to create a place that engages each child.</h3>
               <div class="text-secondary fs-6 pt-3">Praesent arcu gravida vehicula est node maecenas loareet morbi a dosis luctus. Urna eget lacinia eleifend praesent luctus a arcu quis facilisis venenatis. Aenean interdum, nibh vitae sodales, magna ante feugiat elit maecenas.</div>
               <ul class="mt-4">
                  <li class="d-flex pb-3">
                     <img src="/images/style_1.png" alt="checkbox">
                      <div class="text-secondary ms-2">Comprehensive reporting on individual achievement</div>
                  </li>
                        <li class="d-flex pb-3">
                     <img src="/images/style_1.png" alt="checkbox">
                      <div class="text-secondary ms-2">Educational field trips and school presentations</div>
                  </li>
                        <li class="d-flex pb-3">
                     <img src="/images/style_1.png" alt="checkbox">
                      <div class="text-secondary ms-2">Individual attention in a small-class setting</div>
                  </li>
                        <li class="d-flex pb-3">
                     <img src="/images/style_1.png" alt="checkbox">
                      <div class="text-secondary ms-2">Learning program with after-school care</div>
                  </li>
                        <li class="d-flex pb-3">
                     <img src="/images/style_1.png" alt="checkbox">
                      <div class="text-secondary ms-2">Opportunities to carry out scientific investigations</div>
                  </li>
                        <li class="d-flex pb-3">
                     <img src="/images/style_1.png" alt="checkbox">
                      <div class="text-secondary ms-2">Positive learning environment for your child</div>
                  </li>
               </ul>
           </div>
           <div class="col-6">
            <ul class="d-flex flex-wrap mt-5">
                <li class="d-flex flex-column w-50">
                    <figure class="xsmall-rounded bg-white">
                        <img src="/images/toy.png" alt="train">
                    </figure>
                    <h4 class="text-center">Learning and Fun</h4>
                    <p class="text-secondary text-center">Praesent modea est gravida node vehicula luctus.</p>
                </li>
                 <li class="d-flex flex-column w-50">
                    <figure class="xsmall-rounded bg-white">
                        <img src="/images/meal.png" alt="meal">
                    </figure>
                    <h4 class="text-center ms-2">Healty Meal</h4>
                    <p class="text-secondary text-center ms-2">Terminal interdum a eleifend maecenas est morbi.</p>
                </li>
                <li class="d-flex flex-column w-50">
                    <figure class="xsmall-rounded bg-white">
                        <img src="/images/school.png" alt="school">
                    </figure>
                    <h4 class="text-center ms-2">Friendly Place</h4>
                    <p class="text-secondary text-center ms-2">Terminal interdum a eleifend maecenas est morbi.</p>
                </li>
                <li class="d-flex flex-column w-50">
                    <figure class="xsmall-rounded bg-white">
                        <img src="/images/shield.png" alt="shield">
                    </figure>
                    <h4 class="text-center ms-2">Childrean safety</h4>
                    <p class="text-secondary text-center ms-2">Praesent modea est gravida node vehicula luctus.</p>
                </li>
            </ul>

           </div>
        </div>
    </section>
    <!-- Gallery section -->
    <section>
        <div class="gallery d-flex">
          <img src="/images/gallery_01.jpg" alt="">
          <img src="/images/gallery_01.jpg" alt="">
          <img src="/images/gallery_01.jpg" alt="">
          <img src="/images/gallery_01.jpg" alt="">
        </div>
        <div class="banner d-flex justify-content-around align-items-center">
        <div>See Our Kindergarten Photo Gallery!</div>
        <button class="info-button"> VIEW GALLERY <img src="/images/slider_next.png" alt="slider-next"></button>
        </div>
        <div class="full-screen">
           <cite class="citation">
            <figure>
               <img src="/images/quote_alt.png" alt="quote">
            </figure>
            <p class="text-center">I have to say that I have 2 children ages 5 and 2 and have used various daycare's in Kindergarden and this is by far the best I have ever used.</p>
            <div class="bar"></div>
            <div>Cecil J. Kirk</div>
           </cite>
        </div> 
    </section>
  </main>

</template>

<script>

export default {
    name:'TheMain',
}
</script>

<style lang="scss" scoped>
  .title{
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

h3,h4{
    color: #554e9e;
}

figure.odd{
    background-color:  #d2105d;
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
        border:  #d2105d;
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
        background-color:  #d2105d;
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
            background-color: #d2105d;
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
        box-shadow: 0 0  10px  #d2105d;
    }


}

.xsmall-rounded{
    width: 80px;
    height: 80px;
    border-radius: 50%;
    margin: 0 auto;
    margin-bottom: 30px;
    margin-top: 30px;

    img{
        width: 40px;
    }
}

.gallery{

    img{
        width: 400px;
        height: 350px;
    } 
}

 .banner{
            height: 150px;
            background-color: #554e9e;


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
            }


        }

.full-screen{
    height: 500px;
    background-image: url(../../public/images/class_02-690x506.jpg);
    background-repeat: no-repeat;
    background-size: 100%;
    background-position-y: center;
    background-position-x: center;
    opacity: 80%;

    .citation{
        color: #fff;
        width: 400px;
        text-align: center;
        position: relative;
        top: 50px;

        figure{
            border: 1px solid white;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin: 0 auto;
            
            
        }

        p{
            width: 70%;
            font-size: 2.2rem;
            line-height: 50px;
            margin: 10px auto;
        }

        .bar{
            width: 50px;
            height: 1px;
            background-color: #fff;
            margin: 20px auto;
            
        }
    }
}


</style>