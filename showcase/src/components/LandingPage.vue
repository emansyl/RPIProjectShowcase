<template>
    <div>
        
            <!-- <h1 id="headline">Insert a catchy Tag Line Here</h1> -->

            

            <section class="padding-y-xxl position-relative z-index-1">
                <div class="container max-width-adaptive-sm position-relative z-index-2">
                    <!-- <div class="text-sm opacity-60% margin-bottom-xxs">This is a Label</div> -->

                    <section class="cd-intro">
                        <div class="cd-intro-content bouncy">
                            <h1>How do RPI Students Change the world?</h1>
                            <p>A collection of some the most innovative projects at RPI</p>
                            <div class="action-wrapper">
                                <a href="#0" class="cd-btn main-action">Projects</a>
                                
                            </div>
                        </div>
                    </section>
                </div>

                <figure class="bg-decoration z-index-1" aria-hidden="true">
                    <svg class="bg-decoration__svg color-contrast-low" viewBox="0 0 1920 450" fill="none">
                    <rect opacity="0.5" x="1410.61" y="42.6123" width="246.643" height="304.604"
                        transform="rotate(-45 1410.61 42.6123)" fill="url(#bg-decoration-v1-fx-1-linear-1)" />
                    <rect opacity="0.5" x="1176" y="-20.5969" width="246.643" height="304.604" transform="rotate(-45 1176 -20.5969)"
                        fill="url(#bg-decoration-v1-fx-1-linear-2)" />
                    <circle opacity="0.5" cx="1572" cy="205" r="46" fill="url(#bg-decoration-v1-fx-1-radial-1)" />
                    <g opacity="0.5" filter="url(#bg-decoration-v1-fx-1-blur-1)">
                        <circle cx="1680" cy="324" r="26" fill="var(--color-primary)" />
                    </g>
                    <defs>
                        <filter id="bg-decoration-v1-fx-1-blur-1" x="1644" y="288" width="72" height="72" filterUnits="userSpaceOnUse"
                        color-interpolation-filters="sRGB">
                        <feFlood flood-opacity="0" result="BackgroundImageFix" />
                        <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape" />
                        <feGaussianBlur stdDeviation="5" result="effect1_foregroundBlur" />
                        </filter>
                        <linearGradient id="bg-decoration-v1-fx-1-linear-1" x1="1533.93" y1="42.6123" x2="1533.93" y2="347.217"
                        gradientUnits="userSpaceOnUse">
                        <stop stop-color="currentColor" />
                        <stop offset="1" stop-color="currentColor" stop-opacity="0" />
                        </linearGradient>
                        <linearGradient id="bg-decoration-v1-fx-1-linear-2" x1="1299.32" y1="-20.5969" x2="1299.32" y2="284.007"
                        gradientUnits="userSpaceOnUse">
                        <stop stop-color="currentColor" />
                        <stop offset="1" stop-color="currentColor" stop-opacity="0" />
                        </linearGradient>
                        <radialGradient id="bg-decoration-v1-fx-1-radial-1" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse"
                        gradientTransform="translate(1572 205) rotate(90) scale(46)">
                        <stop stop-color="var(--color-primary)" stop-opacity="0" />
                        <stop offset="1" stop-color="var(--color-primary)" />
                        </radialGradient>
                    </defs>
                    </svg>
                </figure>
            </section>




            <body>
                <div>   
                
                    <p id="tagline"> Lorem ipsum dolor sit amet, 
                        consectetur adipiscing elit, 
                        sed do eiusmod tempor incididunt 
                        ut labore et dolore magna aliqua. 
                        Dolor sed viverra ipsum nunc. 
                        Faucibus in ornare quam viverra orci sagittis eu.  
                    </p>
                </div>

                <div id="boxes">
                    <p id="projects">
                        facilisis leo vel fringilla
                    </p>

                    <p id="addproject">
                        pharetra et ultrices neque
                    </p>
                </div>
        </body>
    </div>

    
</template>

<script>
export default {
    name: 'LandingPage',
    
}
</script>

<style scoped>
    .cd-intro-content h1,
.cd-intro-content p,
.cd-intro-content .cd-btn {
  opacity: 0;
  animation-delay: 0.3s;
  animation-fill-mode: forwards;
}

.bouncy.cd-intro-content h1 {
  animation-name: cd-bounce-right;
}

.bouncy.cd-intro-content p {
  animation-name: cd-bounce-left;
}

.bouncy.cd-intro-content h1,
.bouncy.cd-intro-content p {
  animation-duration: 0.6s;
}

.bouncy.cd-intro-content .cd-btn {
  animation-name: cd-bounce-rotate;
  animation-duration: 0.5s;
}

.bouncy.cd-intro-content .cd-btn.main-action {
  animation-delay: 0.4s;
}

@keyframes cd-bounce-right {
  0% {
    opacity: .2;
    transform: translateX(-200px);
  }
  60% {
    opacity: .7;
    transform: translateX(15px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes cd-bounce-left {
  0% {
    opacity: .2;
    transform: translateX(200px);
  }
  60% {
    opacity: .7;
    transform: translateX(-15px);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

@keyframes cd-bounce-rotate {
  0% {
    opacity: .2;
    transform: perspective(800px) rotateX(-80deg);
  }
  20% {
    opacity: 1;
  }
  60% {
    transform: perspective(800px) rotateX(20deg);
  }
  100% {
    opacity: 1;
    transform: perspective(800px) rotateX(0);
  }
}

.bg-decoration {
  position: absolute;
  top: 0;
  left: 0;
  pointer-events: none;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.bg-decoration__svg {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 134%;
  min-width: 1280px;
  max-width: 1920px;
  height: auto;
}
     h1 {
      margin-top: 2em;
      margin-bottom: 2em;
      font-size: 60px;
    } 

    div {
        font-size: 30px;
    }

     #tagline {
        margin: 5em; 
       
    }

     #boxes{
        padding-bottom: 3em;
        margin-bottom: 3em;
     }


</style>