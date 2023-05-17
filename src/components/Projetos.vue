<template>
  <div id="Projetos" class="projetos">
    <h2 class="titulo">Meus Repositórios do GitHub</h2>
    <ul>
      <li v-for="repo in repos" :key="repo.id">
        <a :href="repo.html_url" target="_blank">{{ repo.name }}</a>
      </li>
    </ul>
  </div>
</template>
  
  <script>
  import axios from 'axios';
  
  export default {
    data() {
      return {
        repos: [],
        apiUrl: 'https://api.github.com/users/igorjb360/repos'
      };
    },
    mounted() {
      this.getRepos();
    },
    methods: {
      async getRepos() {
        try {
          const response = await axios.get(this.apiUrl, {
            headers: {
              Authorization: 'GITHUB_TOKEN'
            }
          });
          this.repos = response.data;
        } catch (error) {
          console.error(error);
        }
      }
    }
  }
  </script>
  <style>
  .projetos {
  max-width: 500px;
  margin: 0 auto;
  }
  .titulo{
    margin-bottom: 30px;
  }
  .projetos ul {
  list-style: none;
  padding: 0;
}
.projetos li  {
  margin-bottom: 10px;
  background-color: #f8f8f8;
  padding: 10px;
  border-radius: 5px;
  transition: all 0.2s ease-in-out;
  margin-bottom: 20px;
}
.projetos li:hover {
  transform: translateY(-5px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}
.projetos li a {
  color: #0077b5;
  text-decoration: none;
}

.projetos li a:hover {
  text-decoration: underline;
}
</style>
  