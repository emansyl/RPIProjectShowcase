<template>
    <div>
        
            <!-- <h1 id="headline">Insert a catchy Tag Line Here</h1> -->

            <section class="cd-intro">
                <div class="cd-intro-content bouncy">
                    <h1>How do RPI Students Change the world?</h1>
                    <p>A collection of some the most innovative projects at RPI</p>
                    <div class="action-wrapper">
                        <a href="#0" class="cd-btn main-action">Projects</a>
                        <a href="#0" class="cd-btn">About</a>
                    </div>
                </div>
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