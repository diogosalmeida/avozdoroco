<template>
  <div>
    
      <a name="Projeto"> 
        <p id="title-about">
        Podcast que celebra experiências de arte, educação e cultura,<br />
        segmentos que são essenciais para a nossa sociedade.
        </p>
     </a>
    
    <div id="container-text">
      <p class="full-text">
        O projeto nasceu a partir da idealização do professor-artista,
        apresentador e gestor cultural Guilherme Canto, que em meio à pandemia
        lançou uma série de lives intitulada Rouco Louco, que dialogava com
        artistas e profissionais da área cultural, permanecendo o desejo de
        migrar para outra plataforma e expandir esse projeto que tem por intuito
        democratizar experiências transformadoras que acontecem por aí afora.
      </p>

      <p class="full-text">
        <span id="el-pink">Caramicco</span>, músico, ator e radialista, compõe
        então a equipe e assume a direção e produção técnica do Podcast.
        <span id="el-pink">Tony Berchmans</span>, compositor e pianista já
        parceiro das lives com a trilha sonora, compõe uma música personalizada
        para o projeto, rearranjando uma composição de sua autoria.<span
          id="el-pink"
        >
          Renato Munhoz</span
        >, premiado ilustrador e artista visual, entra com a criação primorosa
        de toda a identidade visual.
      </p>

      <p class="full-text">
        Assim, o projeto nasce, em meados de 2020, produzindo conteúdo artivista
        e dando voz às experiências que não estão sendo ouvidas e valorizadas
        neste tempo em que vivemos. Somos todos roucos, sedentos de mais espaço
        e oportunidade para que nossas vozes possam ressoar pelo mundo afora.
      </p>
      <p class="full-text">
        E assim, o Podcast com essa missão propagadora e pretensiosa, estreia no
        começo de 2021 com episódios inéditos semanais em todas as plataformas
        de streaming de áudio.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style>
#title-about {
  color: #eda430;
  font-size: 38pt;
  font-family: "Roboto Slab", serif;
  text-align: center;
}

#container-text {
  padding: 4rem;
}

.full-text {
  font-size: 18pt;
  font-family: "Dosis", sans-serif;
  text-align: center;
  text-align: inherit;
  color: #293362;
}

#el-pink {
  color: #ed45a2;
}
</style>