<template>
<div class="">
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
    </a>

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
  <div id="nav" class="navbar-end">
      <router-link :to="{ name: 'Home'}">Home</router-link> |
      <router-link :to="{ name: 'About'}">About Us</router-link> |    
      <router-link :to="{ name: 'Contact'}">Contact Us</router-link> |    

  </div>
  </nav>
  </div>
  
    
</template>

<script>
export default {
    
}
</script>

<style lang="css" scoped>
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