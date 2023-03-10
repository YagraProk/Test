<script setup>
import Header from './components/Header.vue'
import Button from '/src/components/Button.vue'
</script>

<template>
  <Header/>
  <div class="main">
    <div class="container">
        <div class="container__inner">
      <p class="text text__main">We are 0.5% on all transaction</p>
      <p class="text text__speech">No catch</p>
      <div><Button/></div>
        </div>
    </div>
  </div>
</template>

<style scoped>

  .main{
    margin-top: 131px;
    display: flex;
    box-sizing:border-box;
    justify-content: center;
    align-items:center;
    
  }

  .container{
    min-width: 671px;
    min-height: 415px;
    background-color: #FFFB47;
    border: 4px solid #000000;
    box-shadow: 12px 12px 4px #000000;
  }

  .container__inner{
    text-align: center;
    padding-top: 136px;
  }

  .text{
    font-size: 32px;
    line-height: 122%;
  }

  .text__main{
    font-family: 'IBM Plex Mono';
    font-weight: 400;
  }

  .text__speech{
    font-family: 'Inter';
    font-weight: 600;
    padding: 33px 266px 85px 266px;
  }

 </style>