<template>
  <div>
    <nav class="navbar navbar-expand navbar-dark bg-dark" aria-label="Second navbar example">
      <div class="container-fluid">
        <a class="navbar-brand" href="/">
          <img class="logo" src="../assets/logo_transparent.png">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarsExample02"
                aria-controls="navbarsExample02" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse justify-content-end" id="navbarsExample02">
          <i class="fa fa-github fa-2x icon-3d"></i>
          <i class="fa fa-gitlab fa-2x icon-3d"></i>
          <i class="fa fa-linkedin fa-2x icon-3d"></i>
          <form>
            <select class="selectpicker form-control" data-width="fit">
              <option>Français</option>
              <option>English</option>
            </select>
          </form>
        </div>
      </div>
    </nav>
    <div class="hero bg-dark">
      <svg class="icone" viewBox="0 0 520 71" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path
          d="M20.6406 48.4844L21.9531 57.4844L23.875 49.375L37.375 1.75H44.9688L58.1406 49.375L60.0156 57.625L61.4688 48.4375L72.0625 1.75H81.1094L64.5625 70H56.3594L42.2969 20.2656L41.2188 15.0625L40.1406 20.2656L25.5625 70H17.3594L0.859375 1.75H9.85938L20.6406 48.4844ZM141.239 38.4531H111.661V62.6406H146.02V70H102.661V1.75H145.551V9.15625H111.661V31.0938H141.239V38.4531ZM177.79 62.6406H210.134V70H168.743V1.75H177.79V62.6406ZM279.029 48.3438C278.185 55.5625 275.513 61.1406 271.013 65.0781C266.544 68.9844 260.591 70.9375 253.154 70.9375C245.091 70.9375 238.622 68.0469 233.747 62.2656C228.904 56.4844 226.482 48.75 226.482 39.0625V32.5C226.482 26.1562 227.607 20.5781 229.857 15.7656C232.138 10.9531 235.357 7.26563 239.513 4.70312C243.669 2.10938 248.482 0.8125 253.951 0.8125C261.201 0.8125 267.013 2.84375 271.388 6.90625C275.763 10.9375 278.31 16.5312 279.029 23.6875H269.982C269.201 18.25 267.497 14.3125 264.872 11.875C262.279 9.4375 258.638 8.21875 253.951 8.21875C248.201 8.21875 243.685 10.3437 240.404 14.5938C237.154 18.8438 235.529 24.8906 235.529 32.7344V39.3438C235.529 46.75 237.076 52.6406 240.169 57.0156C243.263 61.3906 247.591 63.5781 253.154 63.5781C258.154 63.5781 261.982 62.4531 264.638 60.2031C267.326 57.9219 269.107 53.9688 269.982 48.3438H279.029ZM355.377 38.0781C355.377 44.7656 354.252 50.6094 352.002 55.6094C349.752 60.5781 346.564 64.375 342.439 67C338.314 69.625 333.502 70.9375 328.002 70.9375C322.627 70.9375 317.861 69.625 313.705 67C309.549 64.3438 306.314 60.5781 304.002 55.7031C301.721 50.7969 300.549 45.125 300.486 38.6875V33.7656C300.486 27.2031 301.627 21.4062 303.908 16.375C306.189 11.3438 309.408 7.5 313.564 4.84375C317.752 2.15625 322.533 0.8125 327.908 0.8125C333.377 0.8125 338.189 2.14062 342.346 4.79688C346.533 7.42188 349.752 11.25 352.002 16.2812C354.252 21.2812 355.377 27.1094 355.377 33.7656V38.0781ZM346.424 33.6719C346.424 25.5781 344.799 19.375 341.549 15.0625C338.299 10.7187 333.752 8.54688 327.908 8.54688C322.221 8.54688 317.736 10.7187 314.455 15.0625C311.205 19.375 309.533 25.375 309.439 33.0625V38.0781C309.439 45.9219 311.08 52.0938 314.361 56.5938C317.674 61.0625 322.221 63.2969 328.002 63.2969C333.814 63.2969 338.314 61.1875 341.502 56.9688C344.689 52.7188 346.33 46.6406 346.424 38.7344V33.6719ZM392.022 1.75L414.334 57.4375L436.647 1.75H448.319V70H439.319V43.4219L440.163 14.7344L417.756 70H410.866L388.506 14.875L389.397 43.4219V70H380.397V1.75H392.022ZM514.307 38.4531H484.729V62.6406H519.089V70H475.729V1.75H518.62V9.15625H484.729V31.0938H514.307V38.4531Z"
          fill="none" stroke="#5754b0" stroke-width="3"/>
      </svg>
      <p class="line-1 anim-typewriter">Développeur web Fullstack</p>
      <svg class="waves" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
           viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
        <defs>
          <path id="gentle-wave" d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z"/>
        </defs>
        <g class="parallax">
          <use xlink:href="#gentle-wave" x="48" y="0" fill="rgba(255,255,255,0.7"/>
          <use xlink:href="#gentle-wave" x="48" y="3" fill="rgba(255,255,255,0.5)"/>
          <use xlink:href="#gentle-wave" x="48" y="5" fill="rgba(255,255,255,0.3)"/>
          <use xlink:href="#gentle-wave" x="48" y="7" fill="#fff"/>
        </g>
      </svg>
    </div>
    <div class="d-flex justify-content-center">
      <h4 style="margin: 15px">Défilez vers le bas</h4>
    </div>
    <div class="d-flex justify-content-center">
      <div class="chevron"></div>
      <div class="chevron"></div>
      <div class="chevron"></div>
    </div>
    <div class="wrapper">
      <img class="img1" src="../assets/Macbook.png">
      <h2 class="title1">Réda LAMINI<br><span>Développeur Web Fullstack.</span></h2>
    </div>
    <div class="footer bg-dark"/>
  </div>
</template>

<script>
import {gsap} from 'gsap'

export default {
  mounted: function () {
    this.startAnimations()
  },
  methods: {
    startAnimations: function () {
      let tl = new TimelineLite({onUpdate: updatePercentage})

      const scene = this.$scrollmagic.scene({
        triggerElement: '.wrapper',
        triggerHook: 0,
        duration: "500%"
      })
        .setPin(".wrapper")
        .setTween(tl)

      this.$scrollmagic.addScene(scene)

      function updatePercentage(tl) {
        tl.progress()
      }

      tl.to('.img1', 1, {width: "100%", height: "100%"}, 0)
      tl.to('.title1', 0.5, {opacity: 1}, 1)
      tl.to('.profile-picture', 0.5, {opacity: 1}, 1)
      tl.to('.title1', 0.5, {opacity: 0}, 1.5)
      tl.to('.img1', 1, {width: "60%", height: "60%"}, 2)
    }
  }
}
</script>

<style lang="scss">
$redColor: rgba(244, 67, 54, 1);
$blueColor: rgba(33, 150, 243, 1);

.icon-3d {
  padding: 10px;
  -webkit-animation: icon3d 100ms 10;
  animation: icon3d 100ms 10;
  color: #5754b0;

  &:hover {
    -webkit-animation: icon3d 200ms infinite;
    animation: icon3d 200ms infinite;
  }
}

@keyframes icon3d {
  0% {
    text-shadow: 3px 2px $redColor, -3px -4px $blueColor;
  }
  25% {
    text-shadow: -3px -4px $redColor, 4px 3px $blueColor;
  }
  50% {
    text-shadow: 3px -2px $redColor, -6px 2px $blueColor;
  }
  75% {
    text-shadow: -6px -2px $redColor, -3px -2px $blueColor;
  }
  100% {
    text-shadow: -3px -2 $redColor, 3px -2px $blueColor;
  }
}

.line-1 {
  position: relative;
  top: 40%;
  margin: 0 auto;
  border-right: 2px solid rgba(255, 255, 255, .75);
  font-size: 130%;
  text-align: center;
  white-space: nowrap;
  overflow: hidden;
  transform: translateY(-50%);
  color: white;

}

/* Animation */
.anim-typewriter {
  animation: typewriter 3s steps(26) 1s 1 normal both,
  blinkTextCursor 500ms steps(26) infinite normal;
}

@keyframes typewriter {
  from {
    width: 0;
  }
  to {
    width: 14em;
  }
}

@keyframes blinkTextCursor {
  from {
    border-right-color: rgba(255, 255, 255, .75);
  }
  to {
    border-right-color: transparent;
  }
}

.waves {
  position: absolute;
  width: 100%;
  height: 15vh;
  margin-bottom: -7px; /*Fix for safari gap*/
  bottom: 0;
}

.parallax > use {
  animation: move-forever 25s cubic-bezier(.55, .5, .45, .5) infinite;
}

.parallax > use:nth-child(1) {
  animation-delay: -2s;
  animation-duration: 7s;
}

.parallax > use:nth-child(2) {
  animation-delay: -3s;
  animation-duration: 10s;
}

.parallax > use:nth-child(3) {
  animation-delay: -4s;
  animation-duration: 13s;
}

.parallax > use:nth-child(4) {
  animation-delay: -5s;
  animation-duration: 20s;
}

@keyframes move-forever {
  0% {
    transform: translate3d(-90px, 0, 0);
  }
  100% {
    transform: translate3d(85px, 0, 0);
  }
}

.selectpicker {
  @media only screen and (max-width: 480px) { 
    width: 60px;
    height: 30px;
  }
  color: #5754b0;
  background-color: #161618;
  border-color: #5754b0;
}

.selectpicker:focus {
  color: #5754b0;
  background-color: #161618;
  border-color: #5754b0;
}

.selectpicker option {
  @media only screen and (min-width: 480px) { 
    width: 520px;
    height: 75px;
  }
  color: #5754b0;
  background-color: #161618;
  border-color: #5754b0;
}

.logo {
  line-height: 0;
  text-decoration: none;
  height: 100px;
  width: 100px;
}

.header {
  width: 100%;
  height: 6rem;
  display: -webkit-box;
  display: flex;
  justify-content: space-around;
  -webkit-box-align: center;
  align-items: center;
  z-index: 100;
  background-color: #161618;
}

.container-header {
  display: flex;
  -webkit-box-align: center;
  align-items: center;
  -webkit-box-pack: justify;
  justify-content: space-between;
}

@media (min-width: 768px) {
  .header {
    height: 8rem;
  }
}

html {
  box-sizing: border-box;
  font-size: 100%;
}

*, *:before, *:after {
  box-sizing: inherit;
  margin: 0;
  padding: 0;
}

body {
  width: 100%;
  -webkit-font-smoothing: antialiased;
  font-family: 'Anonymous Pro', monospace;
  overflow-x: hidden;
  color: black;
  font-size: 16px;
}

.hero {
  position: relative;
  width: 100%;
  height: 60vh;
}

.footer {
  width: 100%;
  height: 20vh;
}

.wrapper {
  width: 100%;
  height: 100vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  overflow: hidden;
}

.img1 {
  position: center;
  width: 60%;
  height: 60%;
  @media only screen and (max-width: 480px) { 
    width: 30%;
    height: 30%;
}
}

.profil-picture {
  width: 400px;
  height: 400px;
  bottom: 0;
  left: 50%;
  position: absolute
}

.site-title {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10vh;
}

.title1 {
  position: absolute;
  top: 50%;
  left: 50%;
  font-size: 32px;
  transform: translate(-50%, -50%);
  opacity: 0;
  color: white;
}

.title1 span {
  font-size: 24px;
  font-weight: 400;
  display: block;
}

.chevron {
  color: white;
  position: absolute;
  width: 2.1rem;
  height: 0.48rem;
  opacity: 0;
  transform: scale(0.3);
  animation: move-chevron 3s ease-out infinite;
}

.chevron:first-child {
  animation: move-chevron 3s ease-out 1s infinite;
}

.chevron:nth-child(2) {
  animation: move-chevron 3s ease-out 2s infinite;
}

.chevron:before,
.chevron:after {
  content: '';
  position: absolute;
  top: 0;
  height: 100%;
  width: 50%;
  background: #2c3e50;
}

.chevron:before {
  left: 0;
  transform: skewY(30deg);
}

.chevron:after {
  right: 0;
  width: 50%;
  transform: skewY(-30deg);
}

@keyframes move-chevron {
  25% {
    opacity: 1;
  }
  33.3% {
    opacity: 1;
    transform: translateY(2.1rem);
  }
  66.6% {
    opacity: 1;
    transform: translateY(3.1rem);
  }
  100% {
    opacity: 0;
    transform: translateY(4.8rem) scale(0.5);
  }
}

.icone {
  @media only screen and (min-width: 480px) { 
    width: 520px;
    height: 75px;
}
  display: block;
  margin: 0 auto;
  top: 25%;
  left: 50%;
}

.icone path:nth-child(1) {
  stroke-dasharray: 2500px;
  stroke-dashoffset: 2500px;
  animation: anim 15s ease forwards;
}

@keyframes anim {
  to {
    stroke-dashoffset: 0;
  }
}
</style>
