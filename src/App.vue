
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
  }

var x=5;
if (x==5) {
 let audio = new Audio('audios/jesse.mp3')
audio.play() 
}

</script>

<style>
@font-face {
  font-family: "sfbold";
  src: local("sfbold"),
   url(./fonts/SF-Pro.ttf) format("truetype");
}
@font-face {
  font-family: "sf";
  src: local("sf"),
   url(./fonts/SF-Pro-Display-Thin.otf) format("opentype");
}
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
  padding: 0px;
  margin: 0px;

}
img{
  position: absolute;
  top: 46%;
  left: 36%;
  border-radius: 5%;

}
h1{
  position: absolute;
  top: 10%;
  left: 38%;
background: linear-gradient(90deg, rgba(99,0,0,1) 0%, rgba(145,2,2,1) 10%, rgba(200,0,101,1) 20%, rgba(228,0,185,1) 30%, rgba(140,0,199,1) 40%, rgba(83,0,237,1) 50%, rgba(140,0,199,1) 60%, rgba(228,0,185,1) 70%, rgba(200,0,101,1) 80%, rgba(145,2,2,1) 90%, rgba(99,0,0,1) 100%);
  background-size: 400% 400%;
  font-size: 50px;
  font-family: sfbold;
  letter-spacing: 15px;
  font-weight: 600;
  word-spacing: 5px;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  animation: animate 15s reverse infinite;
  height: 50vh;
  
}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}

h2{
  position: absolute;
  top: 20%;
  left: 32%;
background: linear-gradient(90deg, rgba(99,0,0,1) 0%, rgba(145,2,2,1) 10%, rgba(200,0,101,1) 20%, rgba(228,0,185,1) 30%, rgba(140,0,199,1) 40%, rgba(83,0,237,1) 50%, rgba(140,0,199,1) 60%, rgba(228,0,185,1) 70%, rgba(200,0,101,1) 80%, rgba(145,2,2,1) 90%, rgba(99,0,0,1) 100%);
  background-size: 400%;
  font-size: 20px;
  font-family: sf; 
  letter-spacing: 10px;
  font-weight: 600;
  word-spacing: 5px;
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  animation: animate 15s reverse infinite;
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
  bottom: -830px;
  left: -10px;
  font-size:15px;
  letter-spacing: 25px;
text-decoration: none;

}
h3{
  position: relative;
  bottom: 97px;
  left: -90px;;
  text-decoration: none;
}

h4{
  position: relative;
  bottom: 47px;
  left: 90px;
  text-decoration: none;
  
}
</style>

