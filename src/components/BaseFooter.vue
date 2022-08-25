<template>
   <div>
    <div class="maps">
        <iframe class="maps-img" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2801.661184944619!2d-75.67858548459616!3d45.39600507910014!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4cce05ec1d3b9c39%3A0xb4a1e5faf6d358d4!2s77%20Fentiman%20Ave%2C%20Ottawa%2C%20ON%20K1S%200T7%2C%20Canada!5e0!3m2!1sit!2sit!4v1661434256079!5m2!1sit!2sit" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </div>
    <div class="title text-center mt-5">Contact Us</div>
        <h5 class="text-center text-secondary">Our postal adress and contact details</h5>
        <figure>
          <img src="/images/header_divider.png" alt="divider">
        </figure>

        <div class="container">
             <ul class="d-flex justify-content-center my-5">
            <li class="flex-column card-description p-3">
                <figure>
                    <img  class="mt-2" src="/images/envelope (1).png" alt="mail">
                </figure>
                <h3>Postal Address</h3>
                <div>Fable Care Center</div>
                <div>85 Fentiman Ave</div> 
                <div>Ottawa, ON K1S 0T7</div>
            </li>
             <li class="flex-column card-description p-3">
                <figure>
                    <img  class="mt-2" src="/images/mobile.png" alt="mobile">
                </figure>
                <h3>Phone & E-mail</h3>
                <div>Phone: 1-800-64-38</div>
                <div>Fax: 1-800-64-39</div> 
                <a class="text-center d-block" href="#">office@fabel.com</a>
            </li>
             <li class="flex-column card-description p-3">
                <figure>
                    <img  class="mt-2" src="/images/clock.png" alt="schoolbag">
                </figure>
                <h3>Business Hours</h3>
                <div>Monday – Friday</div>
                <div>8.00 am – 5.00 pm</div> 
                <div>Weekend Closed</div>
            </li>
             <li class="flex-column card-description p-3">
                <figure>
                    <img  class="mt-2" src="/images/document (1).png" alt="schoolbag">
                </figure>
                <h3 class="text-center">Sessions</h3>
                <div>Mornings, 8 am – 12 noon</div>
                <div>Afternoons, 1 pm – 5 pm</div> 
                <div>Full Day, 8 am – 5 pm</div>
            </li>
        </ul>
        </div>
    <!-- Form -->
    
        <form class="d-flex">
            <div>
                <input placeholder="Your Name*" type="text" required>
           
                <input placeholder="Your E-Mail*" type="email" required>

                <input placeholder="Subject" type="text" required>
            </div>
            <input class="text-area " placeholder="Your Message*" type="textarea" v-model="textArea">
        </form>
        <button class="message-button">SEND MESSAGE</button>
    </div>
</template>

<script>
export default {
 name: 'BaseFooter',
 data(){
    return{
        textArea: '',
    }
 }
}
</script>

<style lang="scss" scoped>
 .maps{
    width: 100%;
     .maps-img{
        width: 100%;
     }
 }

  .title{
    color: #554e9e;
    font-size: 3rem;
  }

  figure{
    text-align: center;
    padding-top: 20px;
  }

  ul li{
    width: 25%;

    img{

        width: 50px;
        margin-bottom: 10px;
    }

    h3{
        color: #554e9e;
    }
    
    div{
        color: grey;
        text-align: center;
    }
  }

 form{
    width: 600px;
    margin-left: 250px;

    input{

        width: 500px;
        height: 50px;
        margin-bottom: 20px;
    }

    .text-area{

        margin-left: 50px;
        height: 200px;
        text-align: start;
    }
 }
 .message-button{

    background-color:  #d2105d;
    color: #fff;
    border: 1px solid  #d2105d;
    width: 180px;
    height: 50px;
    padding: 5px;
    margin: 10px auto;
    display: block;
 }
</style>