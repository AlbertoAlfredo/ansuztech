<template>
    <div class="banner">
        <div class="banner-text">
        <h1>ANSUZ TECH</h1>
        <h2>A solução para sua empresa</h2>
        </div>
      <img class="banner-img" style="width: 10rem" src="~/assets/img/logo-branco.png">
    </div>
</template>
<style lang="css" scoped>
.banner{
      height: 100%;
      border: 2px #38383800 solid;
      border-radius: 10px;
      padding: 1rem;
      transition: 2s;
      display: flex;
      flex-direction: row;
      font-family: monospace;
      margin: 1%;
      margin-bottom: 4rem;
      align-items: center;
      justify-content: space-between;
      color: #ffffff00;
  }
  .banner:hover{
      border-color: #fff ;
      color: #fff !important;
  }
  .banner-img{
      margin: 2rem;
      margin-right: 6rem;
  }
  .banner-text{
    
    font-size: 4rem;
  }
</style>