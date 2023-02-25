<script>
export default {
    props:{'title': String, 'content': String, 'img': String, 'invert': String},
    data() {
        return {
            inverter: this.invert
        }
    },
}
</script>
<template>
    <div :class="'card ' + invert" >
        <div>
            <h2 class="card-title">{{ title }}</h2>
            <p>{{ content }}</p>
        </div>
        <img :class="'card-img ' + invert" :src="'/_nuxt/assets/img/'+img">
      <slot></slot>
    </div>
</template>
<style lang="css" scoped>
.card{
      height: 100%;
      border: 2px #38383800 solid;
      border-radius: 10px;
      padding: 1rem;
      transition: 2s;
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: space-around;
      margin-bottom: 4rem;
      font-size: 1.2rem;
  }
  .card-title{
    font-size: 2rem;
    font-weight: 700;
  }
  .card:hover{
      border-color: #fff;
  }
  .card-img{
      margin: 2rem;
      width: 20rem;
  }
  .invert{
  flex-direction: row-reverse;
}
</style>