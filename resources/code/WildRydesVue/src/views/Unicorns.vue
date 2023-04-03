<template>
<div class="page-unicorns">
    
    <menus class="site-header" :extraHeader="true" :title="title" :logoColor="'dark'"  />

 <div class="row column medium-10 large-8 xxlarge-6">
    <p class="content">
      A Carreta Furacão tem uma equipe dedicada que recruta, treina e cuida de nosso rebanho de unicórnios. Temos muito orgulho da qualidade dos unicórnios (corredores) que fornecemos aos nossos clientes, e nossa equipe exerce o máximo cuidado ao examinar os unicórnios que se juntam ao nosso rebanho.
    </p>
    <p class="content">
      Todo unicórnio passa por um rigoroso processo de due diligence, onde realizamos verificações de antecedentes, exames de voo e várias rodadas de entrevistas. Os unicórnios aceitos na Carreta Furcão são então tratados com o melhor cuidado e manutenção possível. Oferecemos a eles excelentes benefícios, assistência médica e benefícios aos funcionários. Isso faz parte da filosofia de nossa empresa, na qual unicórnios felizes levam a clientes felizes.
    </p>
    <p class="content">Conheça alguns dos unicórnios que fazem parte da nossa família.</p>
  </div>

  <section class="unicorns-list">

    <div class="row">
      <div class="unicorn jimmy">
        <div class="columns medium-5 large-6 xlarge-5 xlarge-offset-1">
          <img src="images/wr-unicorn-one.png" alt="El diablo">
        </div>

        <div class="columns medium-7 large-6 xlarge-5 xxlarge-4">
          <h2 class="title">El diablo</h2>
          <div class="subtitle">Mais rápido que um furacão</div>
          <p class="content">
            El diablo juntou-se na Carreta Furacão em fevereiro de 2018 e tem feito corridas quase que diariamente. Em seu tempo livre, El diablo gosta de assistir o pôr do sol e jogar Pokemon Go.
          </p>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="unicorn henry">
        <div class="columns medium-5 medium-push-7 large-6 large-push-6 xlarge-5 xlarge-offset-1 xlarge-push-5">
          <img src="images/wr-unicorn-two.png" alt="Dark side">
        </div>

        <div class="columns medium-7 medium-pull-5 large-6 large-pull-6 xlarge-5 xlarge-pull-5 xxlarge-4 xxlarge-offset-1">
          <h2 class="title">Dark side</h2>
          <div class="subtitle">Incrível</div>
          <p class="content">
            Dark side se juntou a Carreta Furacão depois de completar uma distinta carreira corporativa noutra empresa, onde viajou pelo mundo em muitas missões críticas. Dark side gosta de impressionar em suas corridas com truques de mágica que aprendeu com seu dono anterior.
          </p>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="unicorn veronica">
        <div class="columns medium-5 large-6 xlarge-5 xlarge-offset-1">
          <img src="images/wr-unicorn-three.png" alt="Veronica">
        </div>

        <div class="columns medium-7 large-6 xlarge-5 xxlarge-4">
          <h2 class="title">Brabuleta</h2>
          <div class="subtitle">Elegância</div>
          <p class="content">
            Brabuleta juntou-se recentemente à equipe Carreta Furacão em Madrid, Espanha. Ela foi fundamental na formação das operações espanholas da Carreta, após uma longa e distinta carreira de atriz em torneios de sombras de moinhos de vento.
          </p>
        </div>
      </div>
    </div>
  </section>
  <footers />
</div>

</template>

<script>
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'unicórnios',
  data(){
    return{
      title:"Unicórnios são amigos",
      content:"O aplicativo é o que faz esse serviço existir, mas os unicórnios fazem ele se movimentar. Conheça-os e veja com quem você está andando!"
    }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

