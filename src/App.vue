<template>
  <div id="app">
    <v-app>
      <div id="nav">
        <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
          <a class="navbar-brand" href="#"
            ><span style="color:darkgreen; font-size:30px;">4</span
            ><img
              src="https://isl.co/wp-content/uploads/2016/07/vue-logo.png"
              class="logo"
              width="30px"
              height="30px"
              alt="vue"
            />ets</a
          >
          <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarNavDropdown"
            aria-controls="navbarNavDropdown"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <router-link to="/">Home</router-link>
              <router-link to="/about">About</router-link>
              <router-link to="/news">News</router-link>
              <router-link to="/interest">Interest</router-link>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="navbarDropdownMenuLink"
                  role="button"
                  data-toggle="dropdown"
                  aria-haspopup="true"
                  aria-expanded="false"
                >
                  Follow Us
                </a>
                <div
                  class="dropdown-menu"
                  aria-labelledby="navbarDropdownMenuLink"
                >
                  <a
                    class="dropdown-item"
                    href="https://facebook.com"
                    target="_blank"
                  >
                    <i class="fab fa-facebook"></i>
                  </a>
                  <a
                    class="dropdown-item"
                    href="https://linkedin.com"
                    target="_blank"
                  >
                    <i class="fab fa-linkedin"></i>
                  </a>
                  <a
                    class="dropdown-item"
                    href="https://github.com/StephenBrooks220413/"
                    target="_blank"
                  >
                    <i class="fab fa-github"></i>
                  </a>
                </div>
              </li>
            </ul>
          </div>
        </nav>
      </div>
      <router-view />
    </v-app>
  </div>
</template>

<style lang="scss">
@import "./assets/bootstrap.min.css";
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
#nav {
  .navbar-brand {
    padding-top: 4px !important;
  }
  a {
    font-weight: bold;
    color: #2c3e50;
    font-size: 20px !important;
    padding-top: 10px;
    padding-right: 10px;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.social-media-wrapper {
  display: inline-flexbox;
  justify-content: center;
  align-content: center;
  text-align: center;
  padding: 10px;
  letter-spacing: 30px;
  font-size: 27px;

  .social-media-wrapper i {
    color: #2c3e50;
    text-decoration: none;
  }
  i {
    display: inline-block;
  }
}

@media (maxwidth: 1207px) {
  .social-media-wrapper {
    display: flex;
    float: left;
  }
  i {
    display: none;
  }
}
</style>
