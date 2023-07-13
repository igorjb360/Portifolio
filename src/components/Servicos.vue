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
          logo: "https://media.licdn.com/dms/image/C4D0BAQGHrWNA2E_AXQ/company-logo_100_100/0/1676384098738?e=1691020800&v=beta&t=nHoVgw1kvhL17P_Q-XGFmPRxwAZYVYml0k3MUHs7Azo",
          duration: 'Junho 2022 - outubro 2022',
          role: 'Desenvolvedor Full Stack-jr',
          description: 'Responsável pelo desenvolvimento de novas funcionalidades correcoes de bugs no sistema de crediario proprio de grande escala.'
        },
        {
          id: 2,
          name: 'Ditec',
          logo: 'https://educacao.itajai.sc.gov.br/img/geral/logo.jpg',
          duration: 'agosto 2021 - junho 2022',
          role: 'Estagiario-Desenvolvedor web',
          description: 'atuei corrigindo bugs, fazendo melhorias e criando novas funcionalidades no front-end do Sistema da Secretaria de Educação.'
        }
      ]
    }
  }
}
</script>

<style scoped>
.experiencia-section {
<<<<<<< HEAD
  margin-top: 200px;
=======
>>>>>>> origin/master
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
