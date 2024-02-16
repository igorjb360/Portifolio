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
  import Navbar from './views/Navbar.vue'
  import CardDeveloper from './views/Card-developer.vue'
  import Biografia from './views/Biografia.vue'
  import Servicos from './views/Servicos.vue'
  import Projetos from './views/Projetos.vue'
  import Contato from './views/Contato.vue'


  </script>

<style scoped>
.page {
overflow-y: auto;
overflow-x: hidden;
position: absolute;
height: auto;
width: auto;
}

.section-1 {
margin-top: 70px;
width: 100%;
height: 100%; 
margin-bottom: 70px;
}

@media (max-width: 933px) {
  .section-1 {
width: 100%;
height: 100%; 
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