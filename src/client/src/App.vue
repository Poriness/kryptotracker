<template>
  <div id="app">
    <b-container bg-info >
      <navbar-header></navbar-header>
      <router-view />
    </b-container>
  </div>
</template>

<script>
 import NavbarHeader from "@/components/NavbarHeader";
 export default{
   components: {"navbar-header": NavbarHeader},
 }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>





