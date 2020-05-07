<template>
  <div class="container">
    <div>
      <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand to="/">Galerija</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item to="/">Domov</b-nav-item>
            <b-nav-item to="/about/">O nas</b-nav-item>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
         
          
        </b-collapse>
      </b-navbar>
    </div>

    <router-view />
  </div>
</template>

<style>
nav {
  margin-bottom: 24px;
}

/* #app {
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
  color: red;
} */
</style>
