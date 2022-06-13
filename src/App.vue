
<template>

  <home msg="Welcome to Your Vue.js App"/>
</template>

<script>
import home from './components/home.vue'

export default {
  name: 'App',
  components: {
    home
  },
   methods: {
    gotoGoogle() {
      window.open("https://www.google.com");
    },
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
body {
  background-color: black;
  margin: 0;
  padding: 0;
}
h1{
  position: absolute;
  top: 35%;
  left: 33%;
background: linear-gradient(90deg, rgba(255,0,0,1) 0%, rgba(255,231,0,1) 10%, rgba(86,255,0,1) 20%, rgba(0,255,184,1) 30%, rgba(0,245,255,1) 40%, rgba(0,26,255,1) 50%, rgba(145,0,255,1) 60%, rgba(226,0,255,1) 70%, rgba(255,0,189,1) 80%, rgba(255,0,168,1) 90%, rgba(255,0,0,1) 100%);
  background-size: 400%;
  font-size: 100px;
  font-family: Impact;
  letter-spacing: 15px;
  font-weight: 600;
  word-spacing: 5px;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  animation: animate 10s linear infinite;
}

@keyframes animate{
  0%{
    background-position: 0%;
  }

100%{
  rotate: 30px;
background-position: 300%;
}
}
h2{
  position: absolute;
  top: 55%;
  left: 30%;
background: linear-gradient(90deg, rgba(255,0,0,1) 0%, rgba(255,231,0,1) 10%, rgba(86,255,0,1) 20%, rgba(0,255,184,1) 30%, rgba(0,245,255,1) 40%, rgba(0,26,255,1) 50%, rgba(145,0,255,1) 60%, rgba(226,0,255,1) 70%, rgba(255,0,189,1) 80%, rgba(255,0,168,1) 90%, rgba(255,0,0,1) 100%);
  background-size: 400%;
  font-size: 20px;
  font-family: Arial Thin; 
  letter-spacing: 10px;
  font-weight: 600;
  word-spacing: 5px;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  animation: animate 10s linear infinite;
}

@keyframes animate{
  0%{
    background-position: 0%;
  }

100%{
background-position: 300%;
}
}


a{
  position: relative;
  bottom: -525px;
  left: -10px;
  font-size:100px;
  letter-spacing: 25px;
text-decoration: none;

}
h3{
  position: relative;
  bottom: 300px;
  left: -90px;;
}

h4{
  position: relative;
  bottom: 150px;
  left: 90px;
  
}
</style>
