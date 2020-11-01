<template>
  <div id="content">
    <!-- <div class="teaser">
       <div class="teaser-content">
       
        <i class="fas fa-chevron-right"></i>
      </div>
       
    </div> -->

    
   <div class="banner1 delay1">
<img class="teaser" src= "../assets/hero1.png" />
<div class="text-box top">
  <h1 class="mh-text">Kashware is an exclusive <br>ecosystem that unites your money.</h1>
  <p class="mp-text">#Spend #Save #StaySecured #EarnRewards #JoinTheKlub</p>
</div>
   </div>


  <div class="banner2 delay1">
<img class="teaser" src= "../assets/hero2.png" />
<div class="text-box top">
  <h1 class="mh-text1">Kashware is an exclusive <br>ecosystem that unites your money.</h1>
  <p class="mp-text1">#Spend #Save #StaySecured #EarnRewards #JoinTheKlub</p>
</div>
   </div>


<div class="banner3 delay1">
<img class="img3" src= "../assets/hero2.png" />
<div class="text-box t-56">
  <h1 class="mh-text2">Kashware is an exclusive <br>ecosystem that unites your money.</h1>
  <p class="mp-text2">#Spend #Save #StaySecured #EarnRewards #JoinTheKlub</p>
</div>
   </div>

   <div class="banner4 delay1">
<img class="img4" src= "../assets/hero2.png" />
<div class="text-box t-56">
  <h1 class="mh-text3">Kashware is an exclusive <br>ecosystem that unites your money.</h1>
  <p class="mp-text3">#Spend #Save #StaySecured #EarnRewards #JoinTheKlub</p>
</div>
   </div>
     
   <div class="banner5 delay1">
<img class="img5" src= "../assets/Layer 2.png" />
</div> 

<div class="banner6 delay1">
<img class="img6" src= "../assets/kashware kard1.png" />
</div> 

 <div class="banner7 delay1">
<img class="img7" src= "../assets/kashware kard.png" />
</div> 

<div class="banner8 delay1">
<img class="img8" src= "../assets/kashware kard.png" />
</div> 

<div class="banner9 delay1">
<img class="img9" src= "../assets/kashware kard.png" />
</div>



<div class="banner10 delay1">
<img class="img10" src= "../assets/Kard Fan.png" />

<div class="text-box">
  <h1 class="mh-text10">One App. One Card.<br> For all others.</h1>
  
</div>
</div>


  </div>

</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.top{
  top:0;
}
.t-56{
top:56px;
}
.btm-0{
bottom: 0;
}
.mp-text{
  font: normal normal 600 22px/30px SF Pro Display;
    letter-spacing: 0px;
    color: #AAA6A1;
    opacity: 1;
}
.mp-text1{
  font: normal normal 600 20px/30px SF Pro Display;
    letter-spacing: 0px;
    color: #AAA6A1;
    opacity: 1;
}
.mp-text2{
  font: normal normal 600 10px/30px SF Pro Display;
    letter-spacing: 0px;
    color: #AAA6A1;
    opacity: 1;

}
.mp-text3{
  font: normal normal 600 9px/0px SF Pro Display;
    letter-spacing: 0px;
    color: #AAA6A1;
    opacity: 30%;

}
.banner1,.banner2,.banner3,.banner4,.banner5,.banner6,.banner7,.banner8,.banner9,.banner10{
  height: 100vh;
  width: 100%;
  position: absolute;
  left: 0;
  right: 0;
text-align: center;
}

.img3{
  width: 70%;
  height: 400px;
}
.img4{
  width: 60%;
  height: 400px;
}
.img5{
  width: 60%;
  height: 400px;
}
.img6{
  width: 60%;
  height: 400px;
}
.img7{
  width: 60%;
  height: 400px;
}
.img8{
  height: 45%;
    // padding: 3rem;/
}
.img9{
  height: 45%;
    // padding: 3rem;
}
.img10{
  height: 45%;
    // padding: 3rem;
}

.mh-text{
 height: 192px;
    font: normal normal bold 34px/42px SF Pro Display;
    /* letter-spacing: 0px; */
    color: #E5DFD8;
    opacity: 1;

}
.mh-text1{
  height: 192px;
    font: normal normal bold 34px/42px SF Pro Display;
    /* letter-spacing: 0px; */
    color: #E5DFD8;
    opacity: 1;
}
.mh-text2{
 height: 192px;
    font: normal normal bold 18px/32px SF Pro Display;
    /* letter-spacing: 0px; */
    color: #E5DFD8;
    opacity: 1;
}
.mh-text3{
  height: 192px;
    font: normal normal bold 15px/30px SF Pro Display;
    /* letter-spacing: 0px; */
    color: #E5DFD8;
    opacity: 1;
}
.mh-text10{
  height: 192px;
    font: normal normal bold 24px/42px SF Pro Display;
    /* letter-spacing: 0px; */
    color: #E5DFD8;
    opacity: 1;
}
.text-box{
width: 100%;
position: absolute;
color:white;
text-align: center;
// top: 200px;
// left: 100px;
}
.banner1{
  animation: slide1 12s linear  infinite;
}
.banner2{
  animation: slide2 12s linear  infinite;
}
.banner3{
  animation: slide3 12s linear  infinite;
}
.banner4{
  animation: slide4 12s linear  infinite;
}
.banner5{
  animation: slide5 12s linear  infinite;
}
.banner6{
  animation: slide6 12s linear  infinite;
}
.banner7{
  animation: slide6 12s linear  infinite;
}
.banner8{
  animation: slide8 12s linear  infinite;
}
.banner9{
  animation: slide9 12s linear  infinite;
}
.banner10{
  animation: slide10 12s linear  infinite;
}


@keyframes slide1{
  0%{
    visibility: visible;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide2{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: visible;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide3{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: visible;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide4{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: visible;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide5{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: visible;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide6{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: visible;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide7{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: visible;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide8{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: visible;
  }
  80%{
    visibility: hidden;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide9{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  80%{
    visibility: visible;
  }
  90%{
    visibility: hidden;
  }
   100%{
    visibility:hidden;
  }
}

@keyframes slide10{
  0%{
    visibility: hidden;
  }
   10%{
    visibility: hidden;
  }
   20%{
    visibility: hidden;
  }
   30%{
    visibility: hidden;
  }
  40%{
    visibility: hidden;
  }
  50%{
    visibility: hidden;
  }
  60%{
    visibility: hidden;
  }
  70%{
    visibility: hidden;
  }
  90%{
    visibility: visible;
  }
   100%{
    visibility: hidden;
  }
  80%{
    visibility:hidden;
  }
}


.delay1{
  // animation-duration: 9s;
  // animation-delay: 20s;
  transition: opacity .10s ease-in-out;
  -moz-transition: opacity .10s ease-in-out;
  -webkit-transition: opacity .10s ease-in-out;

}

.delay2{
  animation-delay: 12s;
}

.delay3{
  animation-delay: 24s;
}

.delay4{
  animation-delay: 36s;
}

.delay5{
  animation-delay: 48s;
}

.delay6{
  animation-delay: 60s;
}

.delay7{
  animation-delay: 72s;
}

.delay8{
  animation-delay: 84s;
}

.delay9{
  animation-delay: 96s;
}

.delay10{
  animation-delay: 108s;
}







.teaser {
  position: relative;
  width: 100%;
  // max-width: 768px;
  height: 400px;
  margin-bottom: 40px;
//   background-image: url("../assets/hero1.png");
  background-size: cover;
  background-position: top;
  border-radius: 20px;
  overflow: hidden;

  .teaser-content {
    position: absolute;
    left: 20px;
    bottom: 20px;
    width: 210px;
    height: 50px;
    padding: 0 0 0 20px;
    background-color: #111;
    color: #efefef;
    border-radius: 20px;
    font-size: 2rem;
    cursor: pointer;
  }

  i {
    font-size: 1.6rem;
  }
}

.infobox {
  float: left;
  width: 80px;
  height: 80px;
  padding: 10px;
  margin: 0 20px 20px 0;
  border-radius: 20px;
  border: 1px solid #ccc;

  .title {
    font-weight: bold;
  }
  .value {
    padding: 10px 0 0 0;
    font-size: 2rem;
  }
}
</style>
