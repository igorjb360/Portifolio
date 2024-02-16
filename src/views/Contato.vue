<template>
  <div id="Contato" class="contato">
    <footer>
      <div class="container">
      </div>
      <div class="informacoes-contato">
        <div class="icons-contato">
          <a href="https://www.linkedin.com/in/igor-jose-bourscheid-b695651a6/">
            <img src="https://icomoon.io/app/icomoon-lib/icons4acad3d/4/456.svg" alt="icone do linkedin" />
          </a>
          <a href="https://wa.me/47992303661">
            <img src="https://icomoon.io/app/icomoon-lib/icons4acad3d/4/880.svg" alt="icone do whatsapp" />
          </a>
          <a href="https://www.instagram.com/igjbourscheid/">
            <img src="https://icomoon.io/app/icomoon-lib/icons4acad3d/4/387.svg" alt="icone do intagram" style="margin-right: 50px;" />
          </a>
        </div>
        <div class="dados-contato">
          <a>Telefone para Contato:(47) 99230-3661</a>
          <a>Gmail: igorjb360@gmail.com</a>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
</script>
<style>
.contato {
  padding: 0px;
}

footer {
  padding: 20px 0;

}

.container {
  max-width: 960px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}   

.informacoes-contato {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  margin-top: 20px;
}

.icons-contato img {
  transition: all 0.2s ease-in-out;
  width: 24px;
  height: 24px;
  margin-right: 20px;
}
.icons-contato img:hover {
  transform: translateY(-5px);
}

.dados-contato a {
  text-decoration: none;
  margin-right: 20px;
  font-size: 16px;
}

@media screen and (max-width: 768px) {
  .container {
    flex-direction: column;
    align-items: center;
  }

  .redes-sociais a,
  .dados-contato a {
    margin-bottom: 10px;
  }

  .dados-contato a:last-child {
    margin-bottom: 0;
  }
}

</style>