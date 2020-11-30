<svg version="1.1" id="Ebene_1"
    xmlns="http://www.w3.org/2000/svg"
    xmlns:xlink="http://www.w3.org/1999/xlink" height="100px" viewBox="0 0 250 100">
<style>
  body {
    background: #131214;
    height: 100vh;
    overflow: hidden;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-perspective: 500px;
            perspective: 500px;
  }

  #ui {
    -webkit-transform-style: preserve-3d;
            transform-style: preserve-3d;
  }
  #ui .text {
    position: absolute;
    font-size: 10rem;
    color: #fff;
    line-height: 10rem;
    font-family: 'Anton', Impact, fantasy;
    mix-blend-mode: screen;
    -webkit-transform-style: preserve-3d;
            transform-style: preserve-3d;
  }
  #ui .text:nth-child(1) {
    -webkit-clip-path: polygon(-30% 0, -20% 0, 10% 100%, 0% 100%);
            clip-path: polygon(-30% 0, -20% 0, 10% 100%, 0% 100%);
    -webkit-animation: wave 2000ms -10000ms ease-in-out infinite alternate;
            animation: wave 2000ms -10000ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(2) {
    -webkit-clip-path: polygon(-25% 0, -15% 0, 15% 100%, 5% 100%);
            clip-path: polygon(-25% 0, -15% 0, 15% 100%, 5% 100%);
    -webkit-animation: wave 2000ms -9800ms ease-in-out infinite alternate;
            animation: wave 2000ms -9800ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(3) {
    -webkit-clip-path: polygon(-20% 0, -10% 0, 20% 100%, 10% 100%);
            clip-path: polygon(-20% 0, -10% 0, 20% 100%, 10% 100%);
    -webkit-animation: wave 2000ms -9600ms ease-in-out infinite alternate;
            animation: wave 2000ms -9600ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(4) {
    -webkit-clip-path: polygon(-15% 0, -5% 0, 25% 100%, 15% 100%);
            clip-path: polygon(-15% 0, -5% 0, 25% 100%, 15% 100%);
    -webkit-animation: wave 2000ms -9400ms ease-in-out infinite alternate;
            animation: wave 2000ms -9400ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(5) {
    -webkit-clip-path: polygon(-10% 0, 0% 0, 30% 100%, 20% 100%);
            clip-path: polygon(-10% 0, 0% 0, 30% 100%, 20% 100%);
    -webkit-animation: wave 2000ms -9200ms ease-in-out infinite alternate;
            animation: wave 2000ms -9200ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(6) {
    -webkit-clip-path: polygon(-5% 0, 5% 0, 35% 100%, 25% 100%);
            clip-path: polygon(-5% 0, 5% 0, 35% 100%, 25% 100%);
    -webkit-animation: wave 2000ms -9000ms ease-in-out infinite alternate;
            animation: wave 2000ms -9000ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(7) {
    -webkit-clip-path: polygon(0% 0, 10% 0, 40% 100%, 30% 100%);
            clip-path: polygon(0% 0, 10% 0, 40% 100%, 30% 100%);
    -webkit-animation: wave 2000ms -8800ms ease-in-out infinite alternate;
            animation: wave 2000ms -8800ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(8) {
    -webkit-clip-path: polygon(5% 0, 15% 0, 45% 100%, 35% 100%);
            clip-path: polygon(5% 0, 15% 0, 45% 100%, 35% 100%);
    -webkit-animation: wave 2000ms -8600ms ease-in-out infinite alternate;
            animation: wave 2000ms -8600ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(9) {
    -webkit-clip-path: polygon(10% 0, 20% 0, 50% 100%, 40% 100%);
            clip-path: polygon(10% 0, 20% 0, 50% 100%, 40% 100%);
    -webkit-animation: wave 2000ms -8400ms ease-in-out infinite alternate;
            animation: wave 2000ms -8400ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(10) {
    -webkit-clip-path: polygon(15% 0, 25% 0, 55% 100%, 45% 100%);
            clip-path: polygon(15% 0, 25% 0, 55% 100%, 45% 100%);
    -webkit-animation: wave 2000ms -8200ms ease-in-out infinite alternate;
            animation: wave 2000ms -8200ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(11) {
    -webkit-clip-path: polygon(20% 0, 30% 0, 60% 100%, 50% 100%);
            clip-path: polygon(20% 0, 30% 0, 60% 100%, 50% 100%);
    -webkit-animation: wave 2000ms -8000ms ease-in-out infinite alternate;
            animation: wave 2000ms -8000ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(12) {
    -webkit-clip-path: polygon(25% 0, 35% 0, 65% 100%, 55% 100%);
            clip-path: polygon(25% 0, 35% 0, 65% 100%, 55% 100%);
    -webkit-animation: wave 2000ms -7800ms ease-in-out infinite alternate;
            animation: wave 2000ms -7800ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(13) {
    -webkit-clip-path: polygon(30% 0, 40% 0, 70% 100%, 60% 100%);
            clip-path: polygon(30% 0, 40% 0, 70% 100%, 60% 100%);
    -webkit-animation: wave 2000ms -7600ms ease-in-out infinite alternate;
            animation: wave 2000ms -7600ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(14) {
    -webkit-clip-path: polygon(35% 0, 45% 0, 75% 100%, 65% 100%);
            clip-path: polygon(35% 0, 45% 0, 75% 100%, 65% 100%);
    -webkit-animation: wave 2000ms -7400ms ease-in-out infinite alternate;
            animation: wave 2000ms -7400ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(15) {
    -webkit-clip-path: polygon(40% 0, 50% 0, 80% 100%, 70% 100%);
            clip-path: polygon(40% 0, 50% 0, 80% 100%, 70% 100%);
    -webkit-animation: wave 2000ms -7200ms ease-in-out infinite alternate;
            animation: wave 2000ms -7200ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(16) {
    -webkit-clip-path: polygon(45% 0, 55% 0, 85% 100%, 75% 100%);
            clip-path: polygon(45% 0, 55% 0, 85% 100%, 75% 100%);
    -webkit-animation: wave 2000ms -7000ms ease-in-out infinite alternate;
            animation: wave 2000ms -7000ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(17) {
    -webkit-clip-path: polygon(50% 0, 60% 0, 90% 100%, 80% 100%);
            clip-path: polygon(50% 0, 60% 0, 90% 100%, 80% 100%);
    -webkit-animation: wave 2000ms -6800ms ease-in-out infinite alternate;
            animation: wave 2000ms -6800ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(18) {
    -webkit-clip-path: polygon(55% 0, 65% 0, 95% 100%, 85% 100%);
            clip-path: polygon(55% 0, 65% 0, 95% 100%, 85% 100%);
    -webkit-animation: wave 2000ms -6600ms ease-in-out infinite alternate;
            animation: wave 2000ms -6600ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(19) {
    -webkit-clip-path: polygon(60% 0, 70% 0, 100% 100%, 90% 100%);
            clip-path: polygon(60% 0, 70% 0, 100% 100%, 90% 100%);
    -webkit-animation: wave 2000ms -6400ms ease-in-out infinite alternate;
            animation: wave 2000ms -6400ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(20) {
    -webkit-clip-path: polygon(65% 0, 75% 0, 105% 100%, 95% 100%);
            clip-path: polygon(65% 0, 75% 0, 105% 100%, 95% 100%);
    -webkit-animation: wave 2000ms -6200ms ease-in-out infinite alternate;
            animation: wave 2000ms -6200ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(21) {
    -webkit-clip-path: polygon(70% 0, 80% 0, 110% 100%, 100% 100%);
            clip-path: polygon(70% 0, 80% 0, 110% 100%, 100% 100%);
    -webkit-animation: wave 2000ms -6000ms ease-in-out infinite alternate;
            animation: wave 2000ms -6000ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(22) {
    -webkit-clip-path: polygon(75% 0, 85% 0, 115% 100%, 105% 100%);
            clip-path: polygon(75% 0, 85% 0, 115% 100%, 105% 100%);
    -webkit-animation: wave 2000ms -5800ms ease-in-out infinite alternate;
            animation: wave 2000ms -5800ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(23) {
    -webkit-clip-path: polygon(80% 0, 90% 0, 120% 100%, 110% 100%);
            clip-path: polygon(80% 0, 90% 0, 120% 100%, 110% 100%);
    -webkit-animation: wave 2000ms -5600ms ease-in-out infinite alternate;
            animation: wave 2000ms -5600ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(24) {
    -webkit-clip-path: polygon(85% 0, 95% 0, 125% 100%, 115% 100%);
            clip-path: polygon(85% 0, 95% 0, 125% 100%, 115% 100%);
    -webkit-animation: wave 2000ms -5400ms ease-in-out infinite alternate;
            animation: wave 2000ms -5400ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(25) {
    -webkit-clip-path: polygon(90% 0, 100% 0, 130% 100%, 120% 100%);
            clip-path: polygon(90% 0, 100% 0, 130% 100%, 120% 100%);
    -webkit-animation: wave 2000ms -5200ms ease-in-out infinite alternate;
            animation: wave 2000ms -5200ms ease-in-out infinite alternate;
  }
  #ui .text:nth-child(26) {
    -webkit-clip-path: polygon(95% 0, 105% 0, 135% 100%, 125% 100%);
            clip-path: polygon(95% 0, 105% 0, 135% 100%, 125% 100%);
    -webkit-animation: wave 2000ms -5000ms ease-in-out infinite alternate;
            animation: wave 2000ms -5000ms ease-in-out infinite alternate;
  }

  @-webkit-keyframes wave {
    0% {
      -webkit-transform: translate(-50%, -50%) scale(0.9) rotateX(20deg) rotateY(20deg);
              transform: translate(-50%, -50%) scale(0.9) rotateX(20deg) rotateY(20deg);
      color: #f03939;
    }
    100% {
      -webkit-transform: translate(-50%, -50%) scale(1.1) rotateX(0deg) rotateY(0deg);
              transform: translate(-50%, -50%) scale(1.1) rotateX(0deg) rotateY(0deg);
      color: #ed51ff;
    }
  }

  @keyframes wave {
    0% {
      -webkit-transform: translate(-50%, -50%) scale(0.9) rotateX(20deg) rotateY(20deg);
              transform: translate(-50%, -50%) scale(0.9) rotateX(20deg) rotateY(20deg);
      color: #f03939;
    }
    100% {
      -webkit-transform: translate(-50%, -50%) scale(1.1) rotateX(0deg) rotateY(0deg);
              transform: translate(-50%, -50%) scale(1.1) rotateX(0deg) rotateY(0deg);
      color: #ed51ff;
    }
  }

</style>
<div id="ui">
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
  <div class="text">ACCESS DENIED</div>
</div>
</svg>
  
