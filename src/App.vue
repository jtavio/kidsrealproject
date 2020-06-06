<template>
  <div id="app">
    <Menu/>
  
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
    <Footer/>
  </div>
</template>


<script>
import Menu from "@/components/Menu";
import Footer from "@/components/Footer";
export default {
  data(){
    return{
      hover:false
    }
  },
  components:{
    Menu, Footer
  },
  methods:{
 
  }

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow: hidden;
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
.dropdown-item:hover, .dropdown-item:focus {
    background-color: #ff0000 !important;
    color:#ffffff!important;
}

</style>
