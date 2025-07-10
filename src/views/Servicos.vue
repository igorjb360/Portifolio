<template>
  <div class="servicos">
    <h1>Experiência Profissional</h1>

    <div class="experiencia">
      <h2>Assistente de Inovação em TI</h2>
      <p><strong>Empresa:</strong> Escrita Contabilidade de Empresas</p>
      <p><strong>Período:</strong> abr de 2024 - momento - 8 meses</p>
      <p><strong>Local:</strong> Itajaí, Santa Catarina, Brasil - Presencial</p>
      <ul>
        <li>Suporte para sistema de contabilidade</li>
        <li>Criação de novas funcionalidades em micro serviços</li>
        <li>Suporte técnico especializado em hardware e software</li>
        <li>Automação de processos e otimização de operações</li>
        <li>Desenvolvimento utilizando HTML, CSS, JavaScript, React.js, TypeScript e SQL</li>
        <li>Gestão e manutenção de servidores</li>
      </ul>
    </div>

    <div class="experiencia">
      <h2>Técnico de Infraestrutura de TI</h2>
      <p><strong>Empresa:</strong> Lactalis American Group</p>
      <p><strong>Período:</strong> ago de 2023 - mar de 2024 - 8 meses</p>
      <p><strong>Local:</strong> Itajaí, Santa Catarina, Brasil - Presencial</p>
      <ul>
        <li>Administração de Servidores</li>
        <li>Redes e Comunicações</li>
        <li>Suporte Técnico</li>
        <li>Virtualização e Cloud Computing</li>
        <li>Backup e Recuperação de Dados</li>
        <li>Segurança da Informação</li>
        <li>Gerenciamento de Ativos</li>
        <li>Documentação e Relatórios</li>
      </ul>
    </div>

    <div class="experiencia">
      <h2>Analista de Suporte</h2>
      <p><strong>Empresa:</strong> SLTECH Provedor de Serviços Gerenciados em TI</p>
      <p><strong>Período:</strong> jun de 2023 - jul de 2023 - 2 meses</p>
      <p><strong>Local:</strong> Itajaí, Santa Catarina, Brasil - Presencial</p>
      <ul>
        <li>Atender chamados através da plataforma de tickets Tiflux</li>
        <li>Receber chamados dos usuários para resolver diversos tipos de problemas</li>
        <li>Problemas no OneDrive (armazenamento e sincronização na nuvem)</li>
        <li>Problemas na rede da empresa (diagnosticar e solucionar falhas)</li>
        <li>Problemas no servidor (identificar e resolver possíveis falhas no serviço da empresa)</li>
        <li>Criação de VPN para acesso seguro à rede da empresa</li>
        <li>Configuração de estação de trabalho remoto para segurança e funcionamento</li>
        <li>Outras tarefas relacionadas ao suporte técnico em TI</li>
      </ul>
    </div>

    <div class="experiencia">
      <h2>Desenvolvedor Full-Stack Jr</h2>
      <p><strong>Empresa:</strong> Meu Crediário</p>
      <p><strong>Período:</strong> jun de 2022 - out de 2022 - 5 meses</p>
      <p><strong>Local:</strong> Rio do Sul, Santa Catarina, Brasil - Híbrida</p>
      <ul>
        <li>Participação em reuniões diárias com a equipe para alinhamento e progresso dos projetos</li>
        <li>Utilização da plataforma Trello para receber tarefas diárias</li>
        <li>Responsabilidade pela resolução de bugs no desenvolvimento de software</li>
        <li>Criação de novas funcionalidades tanto no front-end quanto no back-end</li>
        <li>Realização de melhorias no front-end e back-end dos sistemas</li>
        <li>Execução de consultas de clientes no banco de dados utilizando a ferramenta DBeaver com linguagem SQL</li>
        <li>Integração com APIs para conectar sistemas ou serviços de terceiros ao software da empresa</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServicosView",
};
</script>

<style scoped>
.servicos {
  padding: 20px;
  font-family: Arial, sans-serif;
  color: #fff;
  text-align: center;
}

h1 {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 30px;
  color: #00aaff;
}

.experiencia {
  margin-bottom: 40px;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

h2 {
  font-size: 1.8rem;
  color: #00aaff;
  margin-bottom: 15px;
  background-color: rgba(255, 255, 255, 0.1);
  padding: 10px;
  border-radius: 8px;
  display: inline-block;
}

p {
  margin: 5px 0;
  font-size: 1rem;
}

ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
}

li {
  line-height: 1.6;
  font-size: 1rem;
  position: relative;
  display: flex;
  align-items: center;
  text-align: left;
  padding-left: 20px;
}

li::before {
  content: "\2022";
  color: #00aaff;
  font-weight: bold;
  display: inline-block;
  width: 1em;
  margin-right: 8px;
}
</style>
