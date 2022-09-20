<template>
  <div>
  <div id="nav">
  <router-link to="/" id="logo-url">
  <img id="logo" :src="logo" :alt="alt" >
  </router-link>
  <router-link to="/">Home</router-link>
  <router-link to="/pedidos">Pedidos</router-link>
  </div>

  </div>
</template>

<script>
export default {
  name:'Navbar',
  props:["logo","alt"]

}
</script>

<style scoped>
 #nav {
    background-color: #222;
    border-bottom: 4px solid #111;
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
  }

  #nav #logo-url {
    margin: auto;
    margin-left: 0;
  }

  #logo {
    width: 60px;
    height: 60px;
  }

  #nav a {
    color: #fcba03;
    text-decoration: none;
    margin: 12px;
    transition: .5s;
  }

  #nav a:hover {
    color: #FFF;
  }

</style>