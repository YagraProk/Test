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
            <img class="section-first-img" src="src\components\images\Image1.png" alt="">
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
                <img src="src\components\images\Vector-arrow.png" alt="">
            </p>
            </div>
            <img class="section-second-img" src="src\components\images\Image2.png" alt="" >
        </section>
        <section class="section section-third">
            <img class="setion-third-img" src="src\components\images\Image3.png" alt="" >
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
    
    .setion-third-img{
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




  

    










    /*
  .header {
    margin: 60px 71px 80px 63px;
  }
    .header__inner{
      box-sizing: border-box;
      display: flex;
      justify-content: space-between;
      max-width: 1512px;
      align-items: center;
      margin: auto;
    }
  
    .logo{
      cursor: default;
    }
  
    .menu {
      max-width: 718px;
    }
  
  .menu__list{
    display: flex;
    justify-content: space-between;
  }
  
  .menu__list-item{
    list-style: none;
    cursor: pointer;
  }
  
  li img{
    padding-left: 10px;
  }
  
  a{
    text-decoration: none;
    color: black;
  }
  
  .item1{
    padding-right: 83.5px;
  }
  
  .item2{
    padding-right: 76px;
  }
  
  .item3{
    padding-right: 72px;
  }
  
  .item4{
    padding-right: 45.5px;
  }
  
  .item5 a{
    border: 2px solid black;
    padding: 10px;
    background-color: #9747FF;
    transition-duration: 0.4s;
    margin-top: -10px;  
    box-shadow: black 2px 2px;
    color: #FFFFFF; 
    font-weight: 700;
  }
  
  .item5 a:hover{
    background-color: #FFFB47; 
    color: black; 
   }
    
  .drop{
    padding: 20px 50px;
    background-color: white;
    position: absolute;
    margin-left: -40px;
    border: 1px solid black;
    display: none;
  }
   .dropmenu {
    background-color: white;
    list-style: none;
    text-align: center;
    padding-top: 5px;
  }
  
  .dropmenu a {
  background-color: white;
  }
  .item1:hover .drop{
  display: block;
  } 
  
  .item2:hover .drop{
  display: block;
  } 
  
  .item3:hover .drop{
  display: block;
  }  */
  </style>
  