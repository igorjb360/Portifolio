<template>
<div class="card-dev">
  <div class="row">
    <div class="col-md-6">
      <img src="../assets/dev_igor.png" class="img-dev img-fluid" alt="Imagem" />
    </div>
    <div class="col-md-6">
      <div class="text-container">
        <div class="card-body">
          <h1 class="titulo">Igor José Bourscheid</h1>
          <b class="cargo">Desenvolvedor/Futuro Cientista da computação</b>
          <p class="subtitulo">Olá, este é o meu portfólio</p>
        </div>
      </div>
    </div>
  </div>
</div>
</template>
<script></script>
<style>
 @media (max-width: 766px) {
  .img-dev{
    align-items: center;
    margin-left: 0% !important;
    width: 50%;
    border-radius: 10px;
  }
 }
.img-dev{
  margin-left: 50%;
  width: 50%;
  border-radius: 10px;
}
@media (max-width: 766px) {
  .card-dev{
 margin-left: 20%;
  }
 }
 @media (max-width: 345px) {
  .card-dev{
    margin-left: 0% !important;
  }
 }
.card-dev {
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
}
.subtitulo{
  font-size: xx-large;
}
</style>
