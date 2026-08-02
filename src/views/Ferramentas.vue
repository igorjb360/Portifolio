<template>
  <div class="ferramentas">
    <h1>Ferramentas</h1>

    <div class="icones">
      <div class="item">
        <img src="@/assets/javascript-icon.svg" alt="JavaScript" />
        <span>JavaScript</span>
      </div>

      <div class="item">
        <img src="@/assets/react-icon.svg" alt="React" />
        <span>React</span>
      </div>

      <div class="item">
        <img src="@/assets/vuejs-icon.svg" alt="Vue.js" />
        <span>Vue.js</span>
      </div>

      <div class="item">
        <img src="@/assets/mysql-icon.svg" alt="MySQL" />
        <span>MySQL</span>
      </div>

      <div class="item">
        <img src="@/assets/typescript-icon.svg" alt="TypeScript" />
        <span>TypeScript</span>
      </div>

      <div class="item">
        <img src="@/assets/angularjs-icon.svg" alt="Angular" />
        <span>Angular</span>
      </div>

      <div class="item">
        <img src="@/assets/html-icon.svg" alt="HTML" />
        <span>HTML</span>
      </div>

      <div class="item">
        <img src="@/assets/css-icon.svg" alt="CSS" />
        <span>CSS</span>
      </div>
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
  padding: 20px;
}

.ferramentas h1 {
  color: #fff;
  font-size: 2.5rem;
  margin-bottom: 50px;
}

.icones {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 45px;
  max-width: 900px;
  margin: 0 auto;
}

.item {
  width: 120px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.item img {
  width: 90px;
  height: 90px;
  object-fit: contain;
  transition: transform .3s ease;
}

.item span {
  margin-top: 12px;
  color: #fff;
  font-size: 15px;
  font-weight: 500;
}

.item:hover img {
  transform: scale(1.15);
}

@media (max-width: 768px) {
  .icones {
    gap: 30px;
  }

  .item {
    width: 100px;
  }

  .item img {
    width: 70px;
    height: 70px;
  }

  .item span {
    font-size: 14px;
  }
}
</style>