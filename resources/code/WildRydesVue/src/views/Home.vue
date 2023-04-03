

<template>
  <div class="home">
   
      <menus class="site-header" showTitle="true" />
    
  <section class="home-about">
    <div class="row column large-9 xlarge-6 xxlarge-4">
      <h2 class="section-title">Como funciona o serviço?</h2>
      <p class="content">
        No mundo acelerado de hoje, você tem lugares que precisa estar, mas não tem tempo suficiente em sua agenda lotada. Não seria bom se existisse um serviço de transporte que mudasse a forma como você se locomove diariamente? Apresentando a Carreta Furacão, um serviço de transporte inovador que ajuda as pessoas a chegarem ao seu destino com mais rapidez e sem complicações. Começar é tão fácil quanto tocar em um botão em nosso aplicativo.
      </p>
    </div>

    <div class="row medium-up-2 large-up-4">
      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-download">Baixe o aplicativo</h3>
          <p class="content">Vá até a loja de aplicativos e baixe o aplicativo Carreta Furacão. Você está a apenas alguns toques de obter sua corrida.</p>
        </div>
      </div>

      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-unicorn">Solicite um Unicórnio</h3>
          <p class="content">Basta solicitar um corredor no aplicativo e nós o conectaremos a um unicórnio imediatamente.Podemos levá-lo até lá.</p>
        </div>
      </div>

      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-price">Escolha um preço</h3>
          <p class="content">Escolha a avaliação que você está disposto a pagar e seu ryde está configurado. O único aumento é a aceleração que você obtém ao decolar.</p>
        </div>
      </div>

      <div class="column">
        <div class="home-about-block">
          <h3 class="title icon-success">Cavalgue para o sucesso!</h3>
          <p class="content">Depois de combinar com seu unicórnio e concordar com seus termos, você estará pronto. Seu unicórnio chegará em breve para buscá-lo.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="home-story">
    <div class="row column large-9 xlarge-6 xxlarge-4">
      <h2 class="section-title">Sobre nós</h2>
      <p class="content">
        A Carreta Furacão foi iniciada por um ex-engenheiro de software de uma grande instituição financeira. Depois de contemplar os majestosos rebanhos de unicórnios empinando em um pôr do sol surreal do rancho Histórias da Vida, o engenheiro testemunhou em primeira mão a pobreza e o desemprego endêmicos daquela outrora orgulhosa raça. Quer tenha sido a confiança da sociedade moderna na ciência sobre a magia ou não, nunca saberemos a causa de sua queda em Neverland e desaparecendo na obscuridade. Movido por empatia, romance e livre iniciativa, ele viu uma oportunidade de casar a demanda da sociedade por transporte mais rápido e flexível com bestas de trabalho subutilizadas por meio de um aplicativo de transporte sob demanda. Usando a experiência de suas respectivas habilidades de criação e engenharia de software, a Carreta Furacão foi formada e, desde então, levantou quantias incontáveis de capital de risco. Hoje, a Carreta Furacão tem milhares de unicórnios em sua rede cumprindo centenas de corridas todos os dias.
      </p>
    </div>
  </section>

  <section class="home-sign-up">
    <div class="row column">

      <form onsubmit="javascript:void(0);">
        <input type="email" placeholder="Insira seu e-mail">
        <button type="button">Enviar</button>
      </form>

      <h2 class="section-title">Cadastrar-se</h2>

      <p class="content">Corridas Selvagem está chegando! Digite seu e-mail para entrar no beta privado limitado.</p>

      <div class="apps">
        <a class="app-icon" href="#"><img src="images/wr-home-apple.png"></a>
        <a class="app-icon" href="#"><img src="images/wr-home-google.png"></a>
      </div>

      <div class="social">
        <a class="icon-fb" href="#">Facebook</a>
        <a class="icon-tw" href="#">Twitter</a>
        <a class="icon-ig" href="#">Instagram</a>
      </div>
    </div>
  </section>

  <section class="home-quote">
    <div class="row column medium-8 xxlarge-6">
      <div class="quote-wrap">
        <div class="quote">
         “Eu estava quase atrasado para o meu último torneio de beach tennis no parque ALEGRIA. Mas a Carreta Furacão me trouxe do destino solicitado em menos de cinco minutos.
        </div>
        <div class="quoter">- Usuário Satisfeito</div>
      </div>
    </div>
  </section>

    <footers />
  </div>
</template>

<script>
// @ is an alias to /src
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'home',
  components: {
    footers: footers,
    menus: menu
  },
}

</script>
