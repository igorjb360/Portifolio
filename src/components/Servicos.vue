<template>
  <div class="experiencia-section" id="Servicos">
    <h2 class="titulo">Experiência Profissional</h2>
    <div class="compania-list">
      <div v-for="company in companies" :key="company.id" class="compania-item">
        <img :src="company.logo" alt="Logo da {{ company.name }}" class="compania-logo">
        <h3>{{ company.name }}</h3>
        <p>{{ company.duration }}</p>
        <p>{{ company.role }}</p>
        <p>{{ company.description }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      companies: [
        {
          id: 1,
          name: 'Meu crediario',
          logo: "https://media.licdn.com/dms/image/C4D0BAQGHrWNA2E_AXQ/company-logo_100_100/0/1676384098738?e=1698883200&v=beta&t=YzPWaVDYQkDHz63uT18rIK7Kpl6_A8VAk6sG4LB_LPQ",
          duration: 'Junho 2022 - outubro 2022',
          role: 'Desenvolvedor Full Stack-jr',
          description: 'Competências: Design de interface do usuário · Web Design Responsivo · Acessibilidade · HTML · CSS · AngularJS · Vue.js · TypeScript · PostgreSQL'
        },
        {
          id: 2,
          name: 'Ditec',
          logo: 'https://educacao.itajai.sc.gov.br/img/geral/logo.jpg',
          duration: 'agosto 2021 - junho 2022',
          role: 'Estagiario-Desenvolvedor web',
          description: 'Competências: Aprendizagem profunda · HTML · CSS · Vuetify · Vue.js'
        }
      ]
    }
  }
}
</script>

<style scoped>
.experiencia-section {
    text-align: center;
  }
  .titulo {
    margin-bottom: 30px;
    }

.compania-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 70px;
}

.compania-logo {
  max-width: 200px;
  margin-bottom: 40px;
}
</style>
