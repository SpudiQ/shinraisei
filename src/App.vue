<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/auth">Auth</router-link>
    <router-link to="/about">About</router-link>
  </nav>

  <header class="header container">

    <div class="logo">
      <img src="../src/assets/logos/MainLogo.png" alt="logo">
    </div>

    <div class="navigation">
      <nav class="nav">
        <a href="/" class="nav-link">Главная</a>
        <a href="" class="nav-link">Категории</a>
        <a href="" class="nav-link">Новости</a>
        <a href="/about" class="nav-link">Контакты</a>
      </nav>
    </div>

    <div class="navigation-logos">

      <a href="">
        <img src="../src/assets/icons/HeaderSearch.png" alt="search">
      </a>
      <a href="">
        <img src="../src/assets/icons/HeaderCart.png" alt="cart">
      </a>
      <a href="">
        <img src="../src/assets/icons/HeaderLogin.png" alt="login">
      </a>

    </div>

  </header>

  <router-view />
  <footer>

  </footer>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Jost:wght@400;500;700&display=swap');

#a, #b, #c, #d {
	object-fit: cover;
	width: 100%;
	height: 92.7vh;
	display: none;
	z-index: 1;
}

*,
*::before,
*::after {
    padding: 0;
    margin: 0;
    border: 0;
    box-sizing: border-box;
}

body {
  background: #0A0A0A;
  margin: 0;
	padding: 0;
}

#app {
  font-family: 'Jost', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
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


.header {
    position: relative;
    width: 100%;
    left: 0;
    top: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}


.nav-link {
    font-size: 24px;
    padding-right: 70px;
    color: #fff;
    text-decoration: none;
}

.navigation-logos img {
    margin-right: 15px;
}

.active {
    text-decoration: underline;
    text-decoration-color: #525252;
    text-decoration-thickness: 2px;
    text-underline-offset: 5px;
}

.container {
    max-width: 1410px;
    padding:  15px;
    margin: 0 auto;
    box-sizing: content-box;
}
</style>
