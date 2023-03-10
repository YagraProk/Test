<template>
    <main class="main">
        <hero class="hero">
            <h1 class="hero__title">
                <span>Start to take</span>  <br/> a change.
            </h1>
            <p class="hero__text">
                Instant, global, and cheap fees. <br/> What more could you asked for?
            </p>
            <div><Button/></div>
        </hero>
        <section class="section section-first">
            <img class="section-first-img" src="src\components\images\Image1.png" alt="Transfer image">
            <h2 class="section-first-title">
                Cheap fees <strong>transfer</strong>, <br/>no fixed cents.
            </h2>
        </section>
        <section class="section section-second">
          <div class="container__text">  
          <h1 class="section-second-title">
                Globally Available!
            </h1>
            <p class="section-second-text">
                We are expanding to over 110+ countries    
            </p>
            <p class="section-second-text">
                See supported countries
                <img src="src\components\images\Vector-arrow.png" alt="Arrow to globe image">
            </p>
            </div>
            <img class="section-second-img" src="src\components\images\Image2.png" alt="Globe image" >
        </section>
        <section class="section section-third">
            <img class="section-third-img" src="src\components\images\Image3.png" alt="Time image" >
            <div class="container__text">  
            <h1 class="section-third-title">
                Time is <span>money.</span>
            </h1>
            <p class="section-third-text">
                Real-time transfer and payouts WORLDWIDE!
            </p>
            <div><Button/></div>
            </div>
        </section>
    </main>    
</template>
  
  <script setup>
  import Button from '/src/components/Button.vue'
  </script>
  
  <style scoped>
    .main{
        max-width: 1300px;
        margin: 0 auto;
    }

    .hero{
        display: flex;
        flex-direction: column;
        text-align: center;
        margin-bottom: 175px;
    }

      .hero__title{
        -webkit-text-stroke: 1px Black;
        padding-bottom: 36px;
    }

    .hero__title span{
        color: #FFFB47;
        text-shadow: 2px 2px 0px #000000;
    }
    
    .hero__text{
        line-height: 122%;
        padding-bottom: 57px;
    }

    .section{
      display: flex;
    }

    .section-first{
      justify-content: space-between;
      margin-bottom: 135px;
    }

    .section-first-title{
      padding-top: 139px;
      padding-right: 37px;
    }

    .section-second {
      display: flex;
      justify-content: space-between;
      margin-bottom: 100px;
    }

    .section-second-title{
      margin-bottom: 36px;
    }
        
    .section-second-text{
      text-align: right;
      padding-bottom: 117px;
    }
    
    .section-third-img{
      padding-right: 65px;
    }

    .section-third-title{
      margin-bottom: 36px;
    }

    .section-third-title span{
      background-color: #BAFFCD;
      color: #37AB00;
    }

    .section-third-text{
      padding-bottom: 128px;
    }
  
  </style>
  