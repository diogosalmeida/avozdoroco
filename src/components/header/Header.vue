<template>
  <div class="container">
    <div class="brother_flex">
      <img id="roco_logo" src="../../assets/logo.svg" />
    </div>
    <div id="podcast" class="brother_flex">
      <h2>Podcast</h2>
    </div>
    <nav id="menu" class="brother_flex">
      <ul>
        <li class="items-menu"><a href="#Projeto">Projeto </a></li>
        <li class="items-menu"><a href="#Equipe">Equipe Rouca </a></li>
        <li class="items-menu"><a href="#Parceiros">Parceiros e Apoiadores </a></li>
        <li class="items-menu"><a href="#Contatos">Contato </a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
.container {
  display: flex;
  background-color: #e9e9e8;
  align-items: center;
}

.brother_flex {
  flex-wrap: wrap;
  flex-direction: row;
}

.items-menu {
  font-weight: bold;
  padding-left: 2px;
}

#podcast {
  font-size: 20pt;
  background-color: #43c29b;
  font-style: #171f53;
  padding: 1rem 1rem 1rem 1rem;
  position: static;
}

#menu {
  margin: auto;
}

#menu ul {
  list-style: none;
  margin-bottom: 10px;
}

#menu ul li {
  display: inline;
  font-size: 18pt;
  padding: 1rem;
}

#menu ul li a {
  padding: 2px 10px;
  display: inline-block;
  color: #333;
  text-decoration: none;
}

#roco_logo {
  height: 10em;
  margin-bottom: -3em;
  padding-right: 1rem;
  padding-left: 1rem;
}
</style>