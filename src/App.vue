<template>
  <div id="app">
    <Header class="neighbors" id="header"></Header>
    <Banner class="neighbors" id="banner"></Banner>
    <Project class="neighbors" id="project"></Project>
    <About id="about"></About>
  </div>
</template>

<script>
import Header from "./components/header/Header";
import Banner from "./components/banner/Banner";
import Project from "./components/project/Project"
import About from "./components/about/About"

export default {
  name: "App",
  components: {
    Header,
    Banner,
    Project,
    About
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
}

#header {
  position: relative;
}

#banner {
  margin: auto;
}
#about {
  margin: auto;
}
</style>
