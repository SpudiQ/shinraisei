<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/auth">Auth</router-link>
  </nav>
  <router-view/>
  <footer>

  </footer>
</template>

<style>

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  background: #0A0A0A;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  margin: 0 5px
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
