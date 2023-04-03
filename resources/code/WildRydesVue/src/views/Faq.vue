<template>
<div class="page-faq">

    <menus class="site-header" :extraHeader="true" :title="title"  />

  <section class="faq-list">
    <div class="row column medium-10 large-8 xxlarge-6">
      <dl>
        <dt>P: Por que devo usar este aplicativo?</dt>
         <dd>R: Unicórnios são mais rápidos, seguros e confiáveis. Nos últimos tempos, seus números cresceram significativamente, atingindo uma escala que torna finalmente possível aproveitá-los para o transporte de massa a um custo acessível.</dd>
         <dt>P: Como você recruta os unicórnios? Como posso saber que meu unicórnio é confiável?</dt>
         <dd>R: Nossos unicórnios são recrutados apenas nas fazendas de unicórnios mais humanas e de alto padrão. Nossos unicórnios são criaturas criadas ao ar livre, alimentadas com capim, com dietas veganas e não transgênicas. Esses unicórnios também são completamente seguros porque os unicórnios têm moralidade e julgamento infalíveis.</dd>
         <dt>P: Como solicito um unicórnio?</dt>
         <dd>R: Basta baixar nosso aplicativo e tocar em um botão para começar. Seu unicórnio chegará em breve.</dd>
         <dt>P: Quanto custa?</dt>
         <dd>R: Como a Carreta Furacão faz parte de um mercado para transporte baseado em voos, o preço que você paga é baseado em fatores como distância e disponibilidade de unicórnios. Você define o preço máximo que está disposto a pagar por uma determinada corrida e, em seguida, a Carreta Furacão combina você com um unicórnio que está disposto a aceitar seu preço.</dd>
         <dt>P: Como funciona?</dt>
         <dd>R: Nosso produto é alimentado por um algoritmo complexo que combina eficientemente unicórnios ociosos com corredores com base em fatores como proximidade e menor tempo até o destino. O sistema é construído em uma arquitetura sem servidor, o que torna a execução e o dimensionamento de nossos serviços de back-end simples e econômicos, permitindo-nos atender de maneira confiável às necessidades da crescente base de usuários da Carreta Furacão.</dd>
         <dt>P: E se eu tiver uma reclamação sobre meu unicórnio?</dt>
         <dd>R: A Carreta Furacão é uma empresa obcecada pelo cliente. Valorizamos cada cliente e queremos garantir uma experiência positiva. Portanto, equipamos nossa equipe de atendimento ao cliente com chatbots sem servidor disponíveis 24 horas por dia, 7 dias por semana para ajudá-lo.</dd>
         <dt>P: Como faço para cancelar minha viagem?</dt>
         <dd>R: Toque no botão "Cancelar Corrida" no aplicativo Carreta Furacão.</dd>
         <dt>P: Posso usar a Carreta Furacão internacionalmente?</dt>
         <dd>R: Sim, você pode usar a Carreta Furacão na maioria dos países, exceto na Antártica, Cuba, Sudão, Irã, Coreia do Norte, Síria e qualquer outro país designado pelo Escritório de Controle de Ativos Estrangeiros do Tesouro dos Estados Unidos.</dd>
         <dt>P: Como pago pelo minha corrida?</dt>
         <dd>R: Depois de criar uma conta na plataforma Carreta Furacão, preencha seu método de pagamento, como cartão de crédito, cartão de débito, carteira Bitcoin ou depósito de gás Vespene. Depois de concluir sua corrida, a tarifa será cobrada automaticamente.</dd>
         <dt>P: Quantos passageiros meu unicórnio pode levar?</dt>
         <dd>R: O número de passageiros em um único passeio depende do tamanho do seu unicórnio. A maioria dos unicórnios pode levar um passageiro por passeio. Você também pode solicitar um unicórnio de tamanho grande que pode levar até dois passageiros. Se você selecionar a versão Trenó, poderá levar até 4 passageiros.</dd>
         <dt>P: E se eu perder um item durante meu passeio?</dt>
         <dd>R: Infelizmente, é improvável que possamos recuperar seu item perdido se ele tiver caído do unicórnio durante o passeio.</dd>
         <dt>P: Como compartilho minhas informações de rota com outra pessoa?</dt>
         <dd>R: Durante o seu passeio, você pode compartilhar sua rota com outra pessoa usando o aplicativo Carreta Furacão. Basta tocar no botão “Compartilhar rota” e selecionar um contato. Em breve, eles poderão monitorar o status da sua corrida.</dd>
         <dt>P: Como avalio meu unicórnio?</dt>
         <dd>R: Depois que seu passeio for concluído, você terá a opção de avaliar seu unicórnio no aplicativo. Nossos unicórnios são obcecados pelo cliente e se esforçam para obter classificações de 5 estrelas. Seu feedback nos ajuda a melhorar nosso serviço!</dd>
         <dt>P: E se meu unicórnio não corresponder à foto no aplicativo?</dt>
         <dd>R: A foto do unicórnio em seu aplicativo deve corresponder ao unicórnio que chega para buscá-lo. Se eles não corresponderem, Wild Rydes recomenda que você não embarque no unicórnio. Você deve então denunciar imediatamente o unicórnio impostor para Wild Rydes.</dd>
         <dt>P: Posso usar GPS com a Carreta Furacão?</dt>
         <dd>R: Sim, você pode conectar seu perfil Concur ao aplicativo Carreta Furacão para poder rastrear viagens de negócios feitas no Carreta Furacão.</dd>
         <dt>P: Posso solicitar um unicórnio específico?</dt>
         <dd>R: Embora não permitamos a solicitação de unicórnios específicos, você pode escolher o tipo e o tamanho do unicórnio usando o aplicativo.</dd>
         <dt>P: Por que vocês cobram uma taxa de serviço?</dt>
         <dd>R: A taxa de serviço é uma taxa fixa adicionada a cada corrida. Isso nos ajuda a pagar por nossos custos operacionais e de manutenção contínuos necessários para um serviço ou cuidados com nosso rebanho de unicórnios.</dd>
      </dl>
    </div>
  </section>
  <footers />
</div>

</template>

<script>
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'faq',
  data(){
    return{
      title:"Perguntas Frequentes",
          }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

