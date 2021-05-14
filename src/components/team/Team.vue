<template>
  <div>
    <div id="container-team">
      <div id="left-logo">
        <img src="../../assets/left-logo.svg" />
      </div>
      <div id="rigth-logo">
        <img src="../../assets/mascote.svg" />
      </div>
    </div>
    <div id="container-team-two">
      <a name="Equipe"><p id="title-rouca">Equipe Rouca</p></a>
      <div class="contact">
        <img class="perfil" src="../../assets/guilheme.svg" />
        <div id="contact-container-perfil">
          <h1 class="title-contact" id="gui" >Guilherme Canto</h1>
          <p class="second-title" id="gui-sub">
            Apresentador, curador e roteirista
          </p>
          <p class="history">
            Artivista, professor-artista nas linguagens visuais e cênicas,
            gestor cultural e comunicador. Apaixonado por pessoas, curioso por
            histórias e comunicador inato. Rouco de nascença e sempre
            questionado por seu timbre de voz, passou a encarar a rouquidão como
            essência e personalidade em seus trabalhos artísticos. Idealizou o
            projeto de Podcast "A Voz do Rouco" com o intuito de contribuir com
            seu sonho e projeto de vida: o dia em que a arte e a educação sejam
            as áreas mais valorizadas para a construção de uma sociedade mais
            justa e democrática.
          </p>
        </div>
      </div>
      <div class="contact">
        <img class="perfil" src="../../assets/digo.svg" />
        <div id="contact-container-perfil">
          <h1 class="title-contact" id="digo">Caramicco</h1>
          <p class="second-title" id="digo">
            Diretor, locutor e produtor técnico
          </p>
          <p class="history">
            Radialista, ator, músico, Caramicco é um artista das diversas
            linguagens. Desde muito pequeno é um apaixonado por comunicação e
            arte, criando seus universos e percebendo seus lugares de
            expressividade. Trabalha também como arte-educador em um grupo de
            teatro estudantil e faz alguns trabalhos como dublador.
            Identificou-se logo de cara com o projeto “A Voz do Rouco”, pois
            acredita que através dele, poderia amplificar uma “Voz” que berra a
            necessidade de difundirmos a verdadeira essência transformadora da
            arte e da educação, na tentativa de desmistificar ideias que
            marginalizam esses ofícios.
          </p>
        </div>
      </div>
      <div class="contact">
        <img class="perfil" src="../../assets/renato.svg" />
        <div id="contact-container-perfil">
          <h1 class="title-contact" id="renato">Renato Lopes</h1>
          <p class="second-title" id="renato">Designer e publicitário</p>
          <p class="history">
            Tem a publicidade e propaganda como formação e a arte e criação como
            paixão. Renato se vê mais voltado para a área de Design mas é “Pau
            pra toda obra”! Quando o chamaram pra fazer parte do projeto não
            pensou duas vezes. Para ele “A Voz do Rouco” é uma chance de muito
            aprendizado e vê muito potencial na iniciativa e por isso está
            disposto a colaborar e ver de pertinho a “Voz” ficar cada vez mais
            forte!
          </p>
        </div>
      </div>
      <div class="contact">
        <img class="perfil" src="../../assets/amanda.svg" />
        <div id="contact-container-perfil">
          <h1 class="title-contact" id="amanda">Maria Amanda</h1>
          <p class="second-title" id="amanda">Comunicadora</p>
          <p class="history">
            Formada em Comunicação Social com habilitação em Rádio, TV e
            Internet, Maria é produtora de TV e de conteúdo para mídias
            digitais. É apaixonada por qualquer tipo de vida e acredita muito no
            trabalho do terceiro setor. Hoje é diretora de comunicação do
            Instituto Defesa Animal e enxerga na A Voz do Rouco uma oportunidade
            de contribuir com a arte-educação do nosso país. Quem sabe do mundo!
          </p>
        </div>
      </div>
      <object class="contact" id="audio"></object>
      <a name="Parceiros">
        <div id="other-container">
          <h1 id="others-voices">
            Outras Vozes
            <p id="parceiros">(Parceiros)</p>
          </h1>
        </div>
      </a>

      <div class="contact">
        <div id="container-final">
          <h1 class="title-contact-cinepiano">
            Tony Berchmans - <span id="cinepiano">Cinepiano</span>
          </h1>
          <a href="http://cinepiano.com/" class="link">http://cinepiano.com/</a>
        </div>
        <img id="cinepiano" src="../../assets/cinepiano.svg" />
      </div>

      <div class="contact" id="cob">
        <div id="container-final">
          <h1 class="title-contact-cinepiano">Rentz</h1>
          <a href="http://rentz.com.br/" class="link">http://rentz.com.br/</a>
        </div>
        <img id="rentz" src="../../assets/rentz.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Team",
};
</script>

<style>
#container-team {
  display: flex;
  justify-content: space-around;
}

#container-team-two {
  display: flex;
  margin-left: 5%;
  margin-top: -32%;
  flex-direction: column;
}

#title-rouca {
  font-size: 75pt;
}

.contact {
  display: flex;
  flex-direction: row;
  align-items: center;
  height: 50%;
}

.title-contact {
  font-size: 45pt;
  padding-bottom: 5%;
}
.second-title {
  font-size: 24pt;
  margin-top: -5%;
}

#contact-container-perfil {
  display: flex;
  flex-direction: column;
}
.history {
  width: 85%;
  font-size: 20pt;
  font-family: "Dosis", sans-serif;
}

#gui {
  color: #20c7a3;
  text-decoration: underline;
}

#gui-sub {
  color: #20c7a3;
}
#digo {
  color: #6b2ea1;
}
#renato {
  color: #f531a7;
}
#amanda {
  color: #72d0f3;
}

#audio {
  margin: auto;
  width: 90%;
  background-image: url(../../assets/audio.svg);
  background-size: cover;
  height: 0;
  padding: 0; /* reset */
  padding-bottom: 92%;
  margin-top: -50%;
}

#others-voices {
  font-size: 45pt;
}
#other-container {
  display: flex;
  flex-direction: row;
  align-content: space-between;
}

.title-contact-cinepiano {
  font-size: 35pt;
  color: #f531a7; 
}

#cinepiano {
  font-weight: normal;
}

.link {
  font-size: 30pt;
  color: #f531a7;
  z-index: 4000;
}

#container-final {
  display: flex;
  flex-direction: column;
}

#cob {
  margin-top: -16%;
}
#parceiros {
  font-size: 40pt;
}
#cinepiano {
  width: 26%;
}

#rentz {
  width: 24%;
}

.perfil {
  width: 35%;
}
</style>