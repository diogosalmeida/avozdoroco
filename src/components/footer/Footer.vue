<template>
  <div>
    <div id="step-one">
      <img id="triangle" src="../../assets/triangle.svg" />
      <a name="Contatos">
        <h1 id="voice">
          A VOZ É SUA
          <p id="contact">(CONTATOS)</p>
        </h1>
      </a>
    </div>

    <div id="step-two">
      <p id="text-contact">
        Você tem duas formas de contatar a gente, além da comunicação pelas
        nossas Redes Sociais. Envie um e-mail ou mande uma mensagem abaixo.
      </p>
    </div>

    <div id="step-tree">
      <p id="email">avozdorouco@gmail.com</p>
    </div>

    <div id="we-channels">
      <h1 id="canais">Nossos Canais</h1>
      <p id="text-contact-one">
        Junte-se a nós e ajude a continuar com esse projeto que ressoa vozes tão
        importantes nesses tempos difíceis em que vivemos.
      </p>

      <p id="text-contact-two">
        Venha fazer parte da nossa família Rouca. Assista o vídeo e saiba como
        você pode ajudar a manter esse projeto vivo!
      </p>
    </div>

    <div id="social-net-working">
      <a href="https://www.instagram.com/avozdorouco/">
        <img class="social" src="../../assets/intagram.svg" />
      </a>

      <a
        href="https://open.spotify.com/show/2Rj3BvM1hCwCTV3DMnvYCd?si=NwQ2OyVKT3eNMM6xZuU8jw&dl_branch=1"
      >
        <img class="social" src="../../assets/spotify.svg" />
      </a>

      <a href="https://www.deezer.com/br/show/2259282">
        <img class="social" src="../../assets/deezer.svg" />
      </a>

      <a href="https://www.facebook.com/guilherme.canto.1612">
        <img class="social" src="../../assets/facebook.svg" />
      </a>

      <a
        href="https://www.google.com/podcasts?feed=aHR0cHM6Ly9hbmNob3IuZm0vcy80YWQ4NGM1NC9wb2RjYXN0L3Jzcw=="
      >
        <img class="social" id="google" src="../../assets/google.svg" />
      </a>

      <a
        href="https://music.amazon.com/podcasts/6901e16f-e075-48c4-8b1e-a22579ed517d/A-Voz-do-Rouco"
      >
        <img class="social" src="../../assets/amazon.svg" />
      </a>
    </div>

    <div id="we-channels">
      <p id="text-contact-one">
        Acesse a nossa página do Apoia-se:
        <a id="link-apoia" href="https://apoia.se/avozdorouco"
          >https://apoia.se/avozdorouco</a
        >
      </p>

      <p id="text-contact-two">PIX - 312.143.508-60 (ou o QR code)</p>
    </div>

    <div id="logo-end">
      <iframe id="iframe" src="https://www.youtube.com/embed/izty0RezH6M">
      </iframe>

      <div id="form-contact">
        <form action="http://formmail.kinghost.net/formmail.cgi" method="POST">
          <input
            type="hidden"
            name="recipient"
            value="testeiseuemail@gmail.com"
          />
          <!-- Pode ser qualquer endereço de email -->
          <input type="hidden" name="redirect" value="http://seudominio" />
          <!-- Após o envio, o usuário será redirecionado para a página configurada aqui -->
          <input type="hidden" name="subject" value="teste de assunto" />
          <!-- Assunto da mensagem -->
          <input type="hidden" name="email" value="email@doseudominio" />
          <!-- Deve ser uma conta de email ativa em seu domínio -->

          <p>
            Nome:<br />
            <input type="text" size="30" name="nome" />
          </p>

          <p>
            E-mail:<br />
            <input type="text" size="30" name="replyto" />
          </p>

          <p>
            Comentários:<br />
            <input type="text" size="35" name="Comentarios" />
          </p>

          <p>
            <input type="submit" id="enviar" name="BTEnvia" value="Enviar" />
          </p>
        </form>
      </div>

      <img id="flor" src="../../assets/flor.svg" />
    </div>
  </div>
</template>

<script>

export default {
  name: "Footer",
};
</script>

<style>
#triangle {
  width: 38%;
  height: 38%;
}

#canais {
  font-size: 35pt;
}

#step-one {
  display: flex;
  margin-top: 5%;
  flex-direction: row;
  justify-content: space-evenly;
}

#step-two {
  display: flex;
  justify-content: center;
  margin-top: 5%;
}

#step-tree {
  display: flex;
  justify-content: center;
}
#contact {
  font-size: 40pt;
  color: #43c29d;
  padding-left: 2%;
}
#voice {
  color: #43c29d;
  font-size: 35pt;
}

#text-contact {
  font-size: 20pt;
  color: white;
  width: 70%;
}

#email {
  color: #f230a6;
  font-size: 25pt;
}

#we-channels {
  display: flex;
  justify-content: initial;
  margin-left: 5%;
  font-size: 30pt;
  color: #f230a6;
  flex-direction: column;
  margin-top: 5%;
}

#text-contact-one {
  width: 70%;
  font-size: 20pt;
  color: white;
  margin-left: 1%;
}
#text-contact-two {
  width: 70%;
  font-size: 20pt;
  color: white;
  margin-left: 1%;
}
#social-net-working {
  display: flex;
  justify-content: space-around;
  align-items: baseline;
  margin-top: 5%;
}
.social {
  position: relative;
  width: 100%;
  height: 60%;
}
#link-apoia {
  color: white;
}

#logo-end {
  margin-top: 10%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}
#flor {
  width: 90%;
  margin-top: -15%;
}

#iframe {
  width: 70%;
  height: 800px;
}
#form-contact {
  margin-left: auto;
  margin-right: auto;
  width: 10em;
  color: white;
  font-size: 22pt;
  margin-top: 5%;
  z-index: 5000;
  font-family: "Dosis", sans-serif;
}

input[type="text"] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
  background: transparent;
  border: none;
  border-bottom: 2px solid #f230a6;
  color: white;
}

#enviar {
  background-color: #43c29d; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  cursor: pointer;
  width: 100%;
}

@media (max-width: 600px)
{
  #triangle
   {
    display: none;
   }
}
</style>