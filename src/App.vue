<script lang="ts">

</script>

<style scoped>
.content{
  background-color: #000;
  overflow-x: hidden;
  overflow-y: hidden;
  font-family: Josefin Sans, sans-serif;
}

.img-thumbnail{
  width: 10%;
}

.elem {
  position: relative;
  background-image: url("../src/assets/img.png");
  background-repeat: no-repeat;
  background-size: cover;
  width: 100vw;
  height: 100vh;
  padding: 0 0 10em 0;
}


.elem::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.3);
}

.text{
  font-size: 1.2em;
  font-weight: bold;
}

.texto-principal{
  margin: 0 0 1em 0;
}
</style>

<template>
 <div  class="content">
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="./assets/URUTU_fundo_preto.jpg" alt="Logo" class="img-thumbnail">
        </a>

        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">

            <li class="nav-item">
              <a class="nav-link" target="_blank" href="https://discord.gg/BADdu5ma">Discord</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

  <div class="elem">
  <main >
      <div class="container ">
        <div class="row">
          <div class="col-8 align-content-center text-white text-xxl-center text">
            <h1>Ei, você!</h1>
            <h2>Já pensou em se juntar a um esquadrão competitivo de War Thunder mas não sabe qual é o melhor?</h2>
          </div>
          <div class="col align-content-center">
            <img src="./assets/URUTU_BRANCA.png"  alt="Logo" class="img-fluid">
          </div>
        </div>

        <div class="row ">
          <div class="col-md-12 text-center  text-white text-xxl-center text texto-principal">
            <h2>Sobre o URUTU</h2>
            <p>O URUTU é um esquadrão brasileiro consolidado no cenário competitivo do War Thunder, se destacando como uma força unificadora entre os clãs latino-americanos, sendo um esquadrão titular da Comunidade Latino-americana de War Thunder (CLAW). Com o objetivo de escalar as classificações e dominar os céus e terras virtuais, o URUTU estabelece alguns critérios para recrutamento, exigindo que os aspirantes possuam veículos de battle rating (BR) 9.0 e demonstrem atividade consistente no jogo. O esquadrão, já contando com mais de 40 membros dedicados, não é apenas um grupo de jogadores habilidosos, mas também um símbolo de camaradagem e estratégia coletiva.
              Juntos, compartilhamos a paixão pelo jogo e o compromisso com a excelência, enquanto nos preparamos para enfrentar desafios e alcançar novos patamares no competitivo mundo de War Thunder.</p>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-md-12 text-center  text-white text-xxl-center text texto-principal">
          <h3>O URUTU nos rankings</h3>
          <p>Atualmente estamos em 183 no ranking da temporada</p>
        </div>
      </div>

  </main>
  </div>
 </div>
</template>
