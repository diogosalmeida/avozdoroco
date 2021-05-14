<template>
  <div id="app">
    <Header class="neighbors" id="header"></Header>
    <Banner class="neighbors" id="banner"></Banner>
    <Project class="neighbors" id="project"></Project>
    <About id="about"></About>
    <Separator class="neighbors"></Separator>
    <Team id="team"></Team>
    <Separator class="neighbors"></Separator>
    <Footer id="footer"></Footer>
  </div>
</template>

<script>
import Header from "./components/header/Header";
import Banner from "./components/banner/Banner";
import Project from "./components/project/Project";
import About from "./components/about/About";
import Separator from "./components/separator/Separator";
import Team from "./components/team/Team";
import Footer from "./components/footer/Footer"

export default {
  name: "App",
  components: {
    Header,
    Banner,
    Project,
    About,
    Separator,
    Team,
    Footer
  },
};
</script>

<style>
#app {
  font-family: Dozis, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: -1rem;
  display: flex;
  flex-direction: column;
  background-color: #e9e9e8;
  padding: 0;
}

#banner {
  margin: auto;
  width: 100%;
}
#about {
  display: flex;
  flex-direction: column;
  align-items: center;
}

#contacts {
  margin: auto;
}

#team {
  background-color: #fccc72;
}

#footer {
  background-color: #171f53;
  width: 100%;
}

@media (max-width: 1400px)
{
  #rigth-logo
   {
    display: none;
   }

   #container-team-two {
     margin-top: -10%;
   }

   .contact {
     padding: 10%;
   }

   #cinepiano {
    display: none;
   }

   #rentz {
     display: none;
   }
}
</style>
