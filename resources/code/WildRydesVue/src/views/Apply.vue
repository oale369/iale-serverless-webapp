<template>
<div class="page-apply">

  <header class="site-header">
    <menus :extraHeader="true" :title="title" :content="content"  />
  </header>
 <section class="content">
    <div class="row column medium-10 large-7 xlarge-5">
      <p>A Carreta Furação está em busca da criatura mais mítica de todas: talentosos engenheiros de software! Estamos procurando uma equipe técnica dos sonhos que nos ajude a construir um futuro onde cada pessoa tenha um unicórnio para criar.</p>
      <p>Do ponto de vista técnico, a Carreta Furacão acredita em um futuro onde não haverá servidores para provisionar, gerenciar ou escalar! Os candidatos interessados podem começar a seguir o Serverless Way explorando as seguintes opções:</p>
      <ul>
        <li>Participe do nosso <a href="#" target="_blank">hackathon</a></li>
        <li>Treine na arte do serverless</li>
      </ul>

      <h2>Serverless Manifesto:</h2>
      <p>As funções são a unidade de implantação e dimensionamento.</p>
      <p>Nenhuma máquina, VM ou contêiner visível no modelo de programação.</p>
      <p>O armazenamento permanente vive em outro lugar.</p>
      <p>Escalas por solicitação. Os usuários não podem fornecer capacidade excessiva ou insuficiente.</p>
      <p>Nunca pague por inatividade (sem servidores/contêineres frios ou seus custos).</p>
      <p>Implicitamente tolerante a falhas porque as funções podem ser executadas em qualquer lugar.</p>
      <p>BYOC - Traga seu próprio código.</p>
      <p>Métricas e registro são um direito universal.</p>
    </div>
  </section>
  <footers />
</div>

</template>

<script>
import footers from '@/components/footer.vue'
import menu from '@/components/menu.vue'

export default {
  name: 'home',
  data(){
    return{
      title:"Documentação"
    }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

