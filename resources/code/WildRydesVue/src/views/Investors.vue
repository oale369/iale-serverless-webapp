<template>
  <div class="page-investors">
      <div class="top-section">
          
            <menus :extraHeader="true" :title="title" :content="content" :logoColor="'dark'"  />

          <div class="investors-list">
                <div class="row">
                  <div class="columns large-4">
                  </div>

                  <div class="columns large-4">
                    <div class="investor">
                    </div>
                  </div>

                  <div class="columns large-4">
                    <div class="investor">
                    </div>
                  </div>
                </div>
          </div>
        </div>


    <section class="board-directors">
        <div class="row">
          <div class="columns large-4 large-push-4">
            <div class="intro block">
              <h2 class="title">Nosso Conselho de Administração</h2>
              <p class="content">
                A Carreta Furacão tem um talentoso Conselho de Administração sobre a estratégia o que possibilita o sucesso dos negócios. Usando seus intangíveis de liderança coletiva, o Conselho trabalha com a Carreta Furacão para criar soluções e formar ideias audaciosas para os desafios de negócios mais prementes da empresa. O Conselho e a Empresa trabalham juntos para tomar decisões informadas sobre a solução de problemas usando otimização de processos e técnicas de tomada de decisão ágil.
              </p>
            </div>
          </div>

          <div class="columns large-4 large-pull-4">
            <div class="one block">
              <h3 class="title">Dr. Forrest Gump</h3>
              <p class="content">Presidente do Conselho.</p>
            </div>
          </div>

          <div class="columns large-4">
            <div class="two block">
              <h3 class="title">Chuck Noland</h3>
              <p class="content">Marketing da Vida.</p>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="columns large-4">
            <div class="three block">
              <h3 class="title">Wilson</h3>
              <p class="content">Sócio na Celeiro.</p>
            </div>
          </div>

          <div class="columns large-4">
            <div class="four block">
              <h3 class="title">Dra. Lari, PhD</h3>
              <p class="content">Sócio-gerente na Capital da Loucura.</p>
            </div>
          </div>

          <div class="columns large-4">
            <div class="five block">
              <h3 class="title">Helen Hunt </h3>
              <p class="content">Presidente do Comitê Central de Planejamento da Carreta Furacão Technology LTDA.</p>
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
  name: '',
  data(){
    return{
      title:"",
      content:""
    }
  },
  components: {
    footers: footers,
    menus: menu
  },
}
</script>

