  <template>
    <div class="page">
      <Navbar></Navbar>
      <section class="section-1">
        <card-developer></card-developer>
      </section>
      <section class="section-2">
          <Biografia></Biografia>
        </section>
        <section class="section-3">
          <Servicos></Servicos>
        </section>
        <section class="section-4">
          <Projetos></Projetos>
        </section>
        <section class="section-5">
          <Contato></Contato>
        </section>
    </div>
  </template>

  <script setup>
  import Navbar from './components/Navbar.vue'
  import CardDeveloper from './components/Card-developer.vue'
  import Biografia from './components/Biografia.vue'
  import Servicos from './components/Servicos.vue'
  import Projetos from './components/Projetos.vue'
  import Contato from './components/Contato.vue'


  </script>

  <style scoped>
    .page {
    overflow-y: auto;
    overflow-x: hidden;
    position: absolute;
    height: 100%;
    width: 100%;
  }

  .section-1 {
    width: 100%;
    height: 100%; 
  }

  @media (max-width: 933px) {
    .section-1{
      /* aqui deixei vazio pois esta conflitando com alguma outra estilização e quebra todo o layout  */
    }
  }

  .section-2 {
    width: 100%;
    height: 100%; 
    margin-bottom: 70px;
  }
  @media (max-width: 933px) {
    .section-2{
      width: auto;
      height: auto;
    }
  }

  .section-3 {
    width: 100%;
    height: 100%; 
  }
  @media (max-width: 933px) {
    .section-3{
      width: auto;
      height: auto;
    }
  }
  .section-4 {
    height: 60%;
  }
  @media (max-width: 933px) {
    .section-4{
      width: auto;
      height: auto;
    }
  }

  </style>
