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
  top: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%; 
}
.section-2 {
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%; 
}
.section-3 {
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%; 
}
.section-4 {
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%; 
}
.section-5 {
  bottom: 0;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%; 
}
</style>
