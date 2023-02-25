<template>
  <div>
    <TheHeader />
    <main class="container">
      <div>
        <!-- <h1>teste</h1>
        <div>
      <h1>São 03:00 da madrugada e agora que consegui fazer funcionar, eu estava correto desde o primeiro teste mas eu estava usando o githubpages para testes e ele não roda legal, ao subir a primeira versão na hostgator funcionou, vou deixar isso aqui para nunca esquecer</h1>
    </div> -->
      </div>
      <div v-for="card in cards">
        <Card 
        :title="card.title"
        :content="card.content"
        :img="card.img"
        :invert="card.invert"
       >
       
       </Card>
      </div>
    </main>
    
  </div>
</template>
<script>
export default {
  data(){
    return {
      cards:[
        {
          title: 'Crie uma presença online impressionante',
          content: 'Com o design certo, você pode criar uma presença online impressionante que destaca sua marca. Seja visto e ouvido em um mercado digital competitivo. Deixe-nos ajudá-lo a criar uma presença online que inspira e atrai seus clientes ideais.',
          img:'1.jpg',
          invert:'invert efeito-amarelo'
        },
        {
          title: 'Design que destaca sua marca em meio à concorrência',
          content: 'Em um mercado digital saturado, o design é fundamental para destacar sua marca. Nós criamos designs exclusivos e inovadores que se destacam da multidão. Não deixe sua marca se perder na concorrência - confie em nós para criar um design que a coloca à frente.',
          img:'2.jpg',
          invert:'efeito-verde'
        },
        {
          title: 'Transforme sua ideia em um site incrível',
          content: 'Sua ideia merece ser vista em toda a sua glória. Deixe-nos transformá-la em um site incrível que irá encantar e envolver seus visitantes. Nós oferecemos design personalizado e soluções técnicas para ajudá-lo a alcançar seus objetivos online.',
          img:'3.jpg',
          invert:'invert efeito-laranja'
        },
        {
          title: 'Design elegante, funcionalidade impecável',
          content: 'Nosso foco é combinar um design elegante com uma funcionalidade impecável para criar uma experiência do usuário excepcional. Oferecemos soluções de design personalizadas que se adaptam às necessidades de sua marca. Confie em nós para criar um design que impressiona visualmente e funciona perfeitamente.',
          img:'4.jpg',
          invert:'efeito-vermelho'
        },
        {
          title: 'Sites que são fáceis de usar e impressionam visualmente',
          content: 'Nós acreditamos que um site deve ser tão fácil de usar quanto é visualmente atraente. É por isso que criamos sites que oferecem a combinação perfeita de beleza e funcionalidade. Deixe-nos ajudá-lo a criar um site que faça sua marca se destacar, enquanto oferece uma experiência de usuário excepcional.',
          img:'5.jpg',
          invert:'invert efeito-amarelo'
        },
      ]
    }
  }
}
  
</script>
<style lang="css" scoped>
    .card-img{
      margin: 2rem;
      margin-right: 6rem;
      width: 5rem;
  }
</style>
<style>
@import url("~/assets/styles/reset.css");
@import url("~/assets/styles/style.css");
</style>
