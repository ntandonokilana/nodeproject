<template>
  <Navbar/>
  <Footer/>
  <Spinner/>

  <router-view/>
</template>

<script>
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';
  import Spinner from './components/Spinner.vue'
  export default{
    components:{
      Navbar,
      Footer,
      Spinner
    },
    data() {
    return {
      loading: true, // Spinner set to true when loading 
    };
  },
    
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

nav {
  padding: 30px;
}

nav a {
   color: black;
    text-decoration: none;
    padding: 10px;
    margin: 5px;
    background-color: #966a32;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

nav a.router-link-exact-active {
  color: #b09813;     /* to be changed */

}

footer {
    text-align: center;
    margin-top: 20px;
    color: #000000;
    position: fixed;
    bottom: 0%;
    width: 100%;
    background-color: whitesmoke; /* to be changed */
  }

</style>

<footer>@ThandoNaturals2024</footer>
