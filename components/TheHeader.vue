<template>
    <div class="banner">
      <img class="banner-img" style="width: 10rem" src="~/assets/img/logo-branco.png">
    </div>
</template>
<style lang="css" scoped>
.banner{
      height: 100%;
      border: 2px #38383800 solid;
      border-radius: 10px;
      padding: 1rem;
      transition: border 2s;
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      margin: 1%;
      margin-bottom: 4rem;
  }
  .banner:hover{
      border-color: #fff ;
  }
  .banner-img{
      margin: 2rem;
      margin-right: 6rem;
  }
</style>