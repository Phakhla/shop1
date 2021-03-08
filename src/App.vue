<template>
  <div id="app">
    <div id="nav">
      <div>
        <b-navbar toggleable="md" type="dark" variant="light">
          <b-navbar-brand href="">
            <b-col sm="1">
              <router-link to="/"
                ><img
                  src="https://scontent.fbkk22-4.fna.fbcdn.net/v/t1.15752-9/p1080x2048/156506991_443042430255417_227756453410202361_n.png?_nc_cat=109&ccb=1-3&_nc_sid=ae9488&_nc_eui2=AeHYjET9u4i2H_1VLNgZEJ3F3BC-yx7RDjLcEL7LHtEOMi59hLtLYicq5paWifZIE8DWFXxuuPesPv8E0AGpotZW&_nc_ohc=uYAe5uveb6MAX8dC0ac&_nc_ht=scontent.fbkk22-4.fna&_nc_tp=30&oh=d1ccadb74618a890e1790e47e8ca5bda&oe=606A3FD1"
                  class="d-inline-block align-top"
                  height="75"
                  width="75"
                />
              </router-link>
            </b-col>
          </b-navbar-brand>
          <b-navbar-toggle  target="nav-collapse"   ></b-navbar-toggle>
          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
              <b-nav-item href="#">
                <b-col sm="1">
                  <router-link to="/order"><h3>Order</h3></router-link>
                </b-col></b-nav-item
              >
              <b-nav-item href="#"
                ><b-col sm="1">
                  <router-link to="/about"><h3>About</h3> </router-link>
                </b-col></b-nav-item
              >
              <b-nav-item href="#">
                <b-col sm="1">
                  <router-link to="/contact"><h3>Contact</h3></router-link>
                </b-col></b-nav-item
              >
            </b-navbar-nav>

            <!-- Right aligned nav items -->

           
          </b-collapse>
        </b-navbar>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 20px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #f8c10ce7;
}
</style>
