<template>
  <div class="home">
    <header id="header">
      <div class="h-container mw1440">
        <div class="logo-box">
          <a href="../home" class="b-head">Sample</a>
        </div>

        <div class="mobile-menu-btn">
          <button v-ripple @click="openMobileNav">
            <v-icon>mdi-menu</v-icon>
          </button>
        </div>
      </div>
    </header>

    <div id="mobile-nav-container" @click="closeMobileNav">
      <div id="mobile-nav-group" class="fs16 uppercase">
        <button class="close-btn" v-ripple @click="closeMobileNav">
          <v-icon>mdi-close</v-icon>
        </button>
        <div class="mobile-nav-box mobile-nav-box-home">
          <button class="nav-item" @click="clickedNav(1)" v-ripple><span>content1</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(2)" v-ripple><span>content2</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(3)" v-ripple><span>content3</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(4)" v-ripple><span>content4</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(5)" v-ripple><span>content5</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(6)" v-ripple><span>content6</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(7)" v-ripple><span>content7</span></button>
        </div>
        <div class="mobile-nav-box">
          <button class="nav-item" @click="clickedNav(8)" v-ripple><span>content8</span></button>
        </div>
      </div>
    </div>
    
    <main>
      <div id="main-img" class=" mw1440">
        <div class="group">
          <div class="text-box padding-20">
            <p class="b-main-head">where do you want to go?</p>
          </div>
          <div class="img-group">
            <div class="img-box padding-20">
              <img src="../assets/main-img/main-img-01.jpg" alt="">
            </div>
            <div class="img-box padding-20">
              <img src="../assets/main-img/main-img-02.jpg" alt="">
            </div>
            <div class="img-box padding-20">
              <img src="../assets/main-img/main-img-03.jpg" alt="">
            </div>
          </div>
        </div>
      </div>
      
      <div id="text1">
        <div class="mw1440">
          <p class="b-head">sample</p>
          <div class="line"></div>
          <p class="b-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
          <div class="input-box fs16">
            <input type="text">
            <button v-ripple>
              <span>summit</span>
            </button>
          </div>
        </div>
      </div>

      <div id="text2" class="mw1440">
        <div class="head-box padding-20">
          <p class="b-head">Lorem Ipsum is simply dummy text</p>
        </div>
        <div class="text-box padding-20">
          <p class="b-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
        </div>
        <div class="text-box padding-20">
          <p class="b-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
            <br>
            <br>
          It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.  
          </p>
        </div>
      </div>

      <div id="photo-view-card" class="mw1440">
        <div class="group">
          <div class="view-box padding-20">
            <img src="../assets/photo-view-card/photo-view-card01.jpg" alt="">
            <div class="text-group padding-40">
              <div class="text-box padding-20">
                <p class="b-title title-line">sample title</p>
                <p class="b-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
              </div>
            </div>
          </div>
          <div class="view-box padding-20">
            <img src="../assets/photo-view-card/photo-view-card02.jpg" alt="">
            <div class="text-group padding-40">
              <div class="text-box padding-20">
                <p class="b-title title-line">sample title</p>
                <p class="b-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
              </div>
            </div>
          </div>
          <div class="view-box padding-20">
            <img src="../assets/photo-view-card/photo-view-card03.jpg" alt="">
            <div class="text-group padding-40">
              <div class="text-box padding-20">
                <p class="b-title title-line">sample tilte</p>
                <p class="b-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div id="counter" class="mw1440">
        <div class="number-bx padding-40">
          <p class="b-main-head">20</p>
          <b class="b-text">sample</b>
        </div>
        <div class="number-bx padding-40">
          <p class="b-main-head">27</p>
          <b class="b-text">sample</b>
        </div>
        <div class="number-bx padding-40">
          <p class="b-main-head">17</p>
          <b class="b-text">sample</b>
        </div>
        <div class="number-bx padding-40">
          <p class="b-main-head">3,986</p>
          <b class="b-text">sample</b>
        </div>
      </div>

      <div id="row-photo-text" class="mw1440">
        <div class="img-box padding-20">
          <img src="../assets/row-photo-text/row-photo-text-01.jpg" alt="">
        </div>
        <div class="img-box padding-20">
          <img src="../assets/row-photo-text/row-photo-text-02.jpg" alt="">
        </div>
        <div class="img-box padding-20">
          <img src="../assets/row-photo-text/row-photo-text-03.jpg" alt="">
        </div>
        <div class="text-box padding-20">
          <div class="inner">
            <p class="b-title title-line">sample title</p>
            <p class="b-text">Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
          </div>
        </div>
      </div>

      <div id="text3" class="mw1440">
        <p class="b-head title-line">sample head</p>
        <p class="b-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
      </div>

      <div id="photo-text-card" class="mw1440">
        <div class="group padding-20">
          <img src="../assets/photo-text-card.jpg" alt="">
          <div class="text-box padding-40">
            <p class="b-head title-line">Contrary to popular belief, Lorem Ipsum is not simply random text.</p>
            <p class="b-text">t has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source.</p>
          </div>
        </div>
      </div>
    </main>


    <footer>
      <div class="f-container mw1440">
        <p class="b-head">sample</p>
        <div class="icon-box">
          <a href="">
            <v-icon>mdi-facebook</v-icon>
          </a>
          <a href="">
            <v-icon>mdi-instagram</v-icon>
          </a>
          <a href="">
            <v-icon>mdi-twitter</v-icon>
          </a>
          <a href="">
            <v-icon>mdi-linkedin</v-icon>
          </a>
        </div>
      </div>
    </footer>
  </div>
</template>


<script>
export default {
  data: () => ({
  }),
  methods:{
    openMobileNav() {
      document.getElementById('mobile-nav-container').style.width = "100%"
      document.getElementById('mobile-nav-group').style.width = "300px"
    },
    closeMobileNav() {
      document.getElementById('mobile-nav-container').style.width = "0"
      document.getElementById('mobile-nav-group').style.width = "0"
    },
    clickedNav(index) {
      if(index == 1) {
        window.scroll({
          top: document.getElementById("main-img").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 2) {
        window.scroll({
          top: document.getElementById("text1").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 3) {
        window.scroll({
          top: document.getElementById("text2").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 4) {
        window.scroll({
          top: document.getElementById("photo-view-card").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 5) {
        window.scroll({
          top: document.getElementById("counter").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 6) {
        window.scroll({
          top: document.getElementById("row-photo-text").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 7) {
        window.scroll({
          top: document.getElementById("text3").offsetTop + -60,
          behavior: 'smooth'
        })
      } else if (index == 8) {
        window.scroll({
          top: document.getElementById("photo-text-card").offsetTop + -60,
          behavior: 'smooth'
        })
      }
      
    },
  }
}
</script>


<style lang="scss" scoped>
// #5EB6EC

/* header */
  header{
    background-color: #fff;
    width: 100%;
    height: 60px;
    position: fixed;
    left: 50%;
    transform: translateX(-50%);
    z-index: 998;
    .h-container{
      background-color: #fff;
      width: 100%;
      height: 60px;
      padding-top: 0;
      padding-bottom: 0;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .b-head{ margin: 0; }
  }
  

  .mobile-menu-btn{
    button{
      color: #5EB6EC;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      .v-icon{ color: #000; }
    }
    button:hover{ background-color: rgba(94, 182, 236, .25); }
  }
  #mobile-nav-container{
    background-color: rgba(0, 0, 0, .8);
    width: 0;
    height: 100vh;
    margin: 0 auto;
    position: fixed;
    top: 0;
    right: 0;
    cursor: pointer;
    z-index: 999;
  }

  #mobile-nav-group{
    background-color: #fff;
    width: 0;
    height: 100vh;
    position: absolute;
    top: 0;
    right: 0;
    transition: .5s;
    overflow: hidden;
    .close-btn{
      color: #5EB6EC;
      width: 40px;
      height: 40px;
      margin: 10px 40px 10px auto;
      border-radius: 50%;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      .v-icon{ color: #000; }
    }
    .close-btn:hover{ background-color: rgba(94, 182, 236, .25); }

    .mobile-nav-box{
      margin: 0 10px;
      padding: 10px;
    }
    .nav-item{
      width: 100%;
      margin: 0;
      border-radius: 5px;
      padding: 14px 0;
      text-align: center;
      color: #5EB6EC;
      span{
        color: #000;
        text-transform: uppercase;
      }
    }
    .nav-item:hover{ background-color: rgba(94, 182, 236, .25); }
  }



/* main */
  #main-img{
    padding-top: 100px;
    .group{ overflow: hidden; }
    .text-box{
      width: 60%;
      margin-left: auto;
      padding-top: 0;
    }
    .b-main-head{
      border-left: 10px solid #c9e8e2;
      padding-left: 24px;
    }
    .img-group{
      display: flex;
      flex-wrap: wrap;
      position: relative;
    }
    .img-box:nth-child(1){
      width: 40%;
      position: absolute;
      bottom: 0;
    }
    .img-box:nth-child(2){ width: 30%; margin-left: auto; }
    .img-box:nth-child(3){ width: 30%; }
  }

  #text1{
    background-color: #c9e8e2;
    text-align: center;
    .mw1440{
      padding-top: 50px;
      padding-bottom: 50px;
    }
    .line{
      background-color: #000;
      width: 100px;
      height: 3px;
      margin: 30px auto;
    }
    .input-box{
      margin-top: 40px;
      input{
        background-color: #fff;
        width: 300px;
        margin-right: 20px;
        padding: 10px 14px;
      }
      input:focus{ box-shadow: 0 0 0 2.5px rgba(255, 255, 255, .5); }
      button{
        background-color: #F7E1D4;
        color: #fff;
        text-transform: uppercase;
      }
      button:hover{ background-color: #F4D6C4; }
      button:focus{ box-shadow: 0 0 0 2.5px #F4D6C4; }
      span{ color: #000; }
    }
  }

  #text2{
    margin-top: 40px;
    display: flex;
    flex-wrap: wrap;
    .head-box{
      width: 25%;
      margin-top: 18px;
      .b-head{
        line-height: 1.5;
        position: relative;
      }
      .b-head:before, .b-head:after{
        content: "";
        width: 100%;
        height: 6px;
        background-color: #D6ECFA;
        position: absolute;
        left: 0;
      }
      .b-head:before{ top: -16px; }
      .b-head:after{ bottom: -16px; }
    }
    .text-box:nth-child(2){ width: 25%; }
    .text-box:nth-child(3){ width: 40%; }
  }

  #photo-view-card{
    .group{
      margin: -20px;
      display: flex;
      flex-wrap: wrap;
    }
    .view-box{ width: 33.33333%; }
    .text-box{
      margin: -80px auto 0;
      position: relative;
      text-align: center;
      .b-title{
        display: inline-block;
        margin: 10px 0 30px;
      }
      .title-line::before, .title-line::after{ background-color: #000; }
    }
    .view-box:nth-child(1) .text-box{ background-color: #F7E1D4; }
    .view-box:nth-child(2) .text-box{ background-color: #D6ECFA; }
    .view-box:nth-child(3) .text-box{ background-color: #c9e8e2; }
  }

  #counter{
    display: flex;
    flex-wrap: wrap;
    .number-bx{
      width: 25%;
      text-align: center;
      .b-head{ margin-bottom: 20px; }
    }
  }

  #row-photo-text{
    display: flex;
    flex-wrap: wrap;
    > div{ width: 25%; }
    .text-box{
      display: flex;
      align-items: center;
      .b-title{
        display: inline-block;
        margin: 30px auto 30px 0;
      }
      .title-line::before, .title-line::after{
        left: 0;
        transform: translateX(0);
      }
    }
  }

  #text3{
    max-width: 1080px;
    text-align: center;
    .b-head{
      margin: 40px 0;
      display: inline-block;
      position: relative;
    }
  }

  #photo-text-card{
    max-width: 1280px;
    .group{
      display: flex;
      flex-wrap: wrap;
      align-items: center;
    }
    img{ width: 54%; }
    .text-box{
      width: 54%;
      margin-left: -8%;
      background-color: #F7E1D4;
      .b-head{ margin: 10px 0 50px 0; }
      .title-line::before, .title-line::after{
        background-color: #000;
        width: 100px;
        left: 0;
        transform: translateX(0);
      }
    }
  }
  


/* footer */
  footer{
    background-color: #eee;
    .f-container{ text-align: center; }
    a{
      margin: 0 5px;
      padding: 5px;
    }
    .v-icon{ color: #000; }
  }





/* 반응형 */
  @media ( max-width: 1080px ) {
    #photo-view-card{
      .text-group{ padding: 10px; }
      .text-box{
        .b-title{ margin: 20px 0 30px; }
      }
    }

    #row-photo-text{
      .text-box{
        .inner{ margin-top: -16px; }
      }
    }

    #photo-text-card{
      .group{ flex-direction: column; }
      img{ width: 80%; }
      .text-box{
        width: 70%;
        margin-top: -5%;
        margin-left: 0;
      }
    }
  }

  @media ( max-width: 980px ) {
    #photo-view-card{
      .view-box{
        width: 100%;
        display: flex;
        align-items: center;
      }
      img{ width: 50%; }
      .text-group{
        width: calc(50% + 40px);
        margin-left: -40px;
        padding: 0;
      }
      .text-box{ margin: 0; }
    }

    #row-photo-text{
      > div{ width: 50%; }
    }

  }

  @media ( max-width: 768px ) {
    #main-img{
      .text-box{ width: 100%; }
      .img-box:nth-child(1){
        background-image: url(../assets/main-img/main-img-01.jpg);
        background-size: cover;
        width: 100%;
        max-height: none;
        margin: 20px;
        padding: calc(100% - 40px) 0 0 0;
        position: relative;
        img{ display: none; }
      }
      .img-box:nth-child(2){ width: 50%; }
      .img-box:nth-child(3){ width: 50%; }
    }

    #text1{
      .line{ margin: 26px auto; }
      .input-box{ margin-top: 30px; }
    }

    #text2{
      .head-box{
        width: 50%;
        margin-top: -6px;
        .b-head{ line-height: 1; margin-top: 26px; }
      }
      .text-box:nth-child(2){ width: 50%; }
      .text-box:nth-child(3){ width: 100%; }
    }

    #counter{
      .number-bx{ width: 50%; }
    }

    #photo-text-card{
      img{ width: 90%; }
      .text-box{
        width: 80%;
        margin-top: -10%;
      }
    }
  }


   @media ( max-width: 650px ) {
     #photo-view-card{
      .view-box{ flex-direction: column; }
      img{ width: 80%; }
      .text-group{
        width: 80%;
        margin-left: 0px;
        padding: 0 40px;
      }
      .text-box{ margin-top: -60px; }
    }
  }


  @media ( max-width: 500px ) {
    #main-img{
      padding-top: 80px;
      .img-box:nth-child(1){
        margin: 10px;
        padding: calc(100% - 20px) 0 0 0;
      }
    }

    #text1{
      .line{ margin: 24px auto; }
      .input-box{
        input{
          width: 100%;
          margin-right: 0px;
          margin-bottom: 10px;
        }
        button{ width: 100%; }
      }
    }

    #text2{
      margin-bottom: 20px;
      .head-box{
        width: 100%;
        text-align: center;
        .b-head{ line-height: 1; }
        .b-head:before, .b-head:after{
          width: 50%;
          left: 50%;
          transform: translateX(-50%);
        }
      }
      .text-box:nth-child(2){ width: 100%; }
      .text-box:nth-child(3){ width: 100%; }
    }

    #photo-view-card{
      margin-bottom: 20px;
      .group{ margin: -10px; }
      .view-box{ margin-bottom: 10px; }
      img{ width: 100%; }
      .text-group{
        width: 100%;
        padding: 0 30px;
      }
    }

    #row-photo-text{
      margin-bottom: 20px;
      > div{ width: 100%; }
    }

    #counter{
      margin-bottom: 20px;
    }

    #text3{
      margin-bottom: 20px;
    }

    #photo-text-card{
      margin-bottom: 20px;
      .group{ margin: -10px; }
      img{ width: 100%; }
      .text-box{
        width: 90%;
        margin-top: -10%;
      }
    }    
  }
</style>