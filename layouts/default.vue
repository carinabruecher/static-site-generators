<template>
  <div class="container">
    <div id="header" class="flex justify-between item-center">
      <h1><nuxt-link class="link-header" to="/">static-site-generators</nuxt-link></h1>
      <div id="menu" class="flex">
        <div><nuxt-link class="menu-link" to="/allgemeines">Allgemeines</nuxt-link></div>
        <div><nuxt-link class="menu-link" to="/funktion">Funktion</nuxt-link></div>
        <div><nuxt-link class="menu-link" to="/vergleich"> Vergleich</nuxt-link></div>
        <div class="link"><nuxt-link class="menu-link" to="/umsetzung">Umsetzung</nuxt-link></div>
      </div>
    </div>
    <nuxt />
  </div>
</template>

<style>

  .container {
    color: black;
    font-family: "Helvetica Neue";
    margin: 0px 0px 0px 0px;
    padding: 0px 0px 0px 0px;

  }

  #header {
    background-color: #fff;
    box-shadow: 0 8px 5px -6px grey;
    padding: 10px 20px 10px 20px ;
    position: fixed;
    top: 0;
    z-index: 900;
    width: 100%;
  }

  .link-header {
    color: black;
    padding-left: 30px;
    text-decoration: none;
  }

  .menu-link {
    color: black;
    padding-left: 10px;
    text-decoration: none;
  }

  .menu-link:hover {
    color: #1d707c;
  }

  #menu {
    padding-top: 10px;
    padding-right: 60px;
  }

  @media (min-width: 600px) {
    .container {
      max-width: 100%;
    }
  }
</style>