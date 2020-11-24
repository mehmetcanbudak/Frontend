<template lang="html">
<div class="">
    <nav class="navbar" role="navigation" aria-label="main navigation">

    <div class="navbar-start">
      <div id="nav">
      <router-link style="text-decoration: none;" :to="{ name: 'Home' }">
        <strong><h1>Mehmetcan Budak</h1></strong>
      </router-link>
    </div>

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>

  </div>

  <div class="navbar-end">
    <div id="nav">
      <router-link :to="{ name: 'Home' }">Home</router-link> |
      <router-link :to="{ name: 'About'}">About Us</router-link> |    
      <router-link :to="{ name: 'Contact' }">Contact Us</router-link> |    
    </div>
  </div>

  </nav>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #42b983;
}

#nav a.router-link-exact-active {
  color: #003366;
}
</style>