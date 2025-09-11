<template>
  <div class="ferramentas">
    <h1>Ferramentas</h1>
    <div class="icones">
      <img src="@/assets/javascript-icon.svg" alt="Ícone do JavaScript" />
      <img src="@/assets/react-icon.svg" alt="Ícone do React" />
      <img src="@/assets/vuejs-icon.svg" alt="Ícone do Vue.js" />
      <img src="@/assets/mysql-icon.svg" alt="Ícone do MySQL" />
      <img src="@/assets/typescript-icon.svg" alt="Ícone do TypeScript" />
      <img src="@/assets/angularjs-icon.svg" alt="Ícone do AngularJS" />
      <img src="@/assets/html-icon.svg" alt="Ícone do HTML" />
      <img src="@/assets/css-icon.svg" alt="Ícone do CSS" />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.ferramentas {
  text-align: center;
  margin-top: 40px;
}

.ferramentas h1 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #fff; /* ajusta pra combinar com fundo */
}

.icones {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 20px;
  justify-items: center;
  align-items: center;
  max-width: 900px;
  margin: 0 auto;
}

.icones img {
  width: 100px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: pointer;
}

.icones img:hover {
  transform: scale(1.15);
  box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.3);
}
</style>
