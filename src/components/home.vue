<template>
  <div class="hello">
    <h2></h2>

<a href="https://github.com/icomrade1">
<v-btn fab icon large color="black">

  <v-icon large color="grey">mdi-github</v-icon>
</v-btn>
</a>

<h4>
  <a href="https://discord.com/users/450430430513070082">
<v-btn icon fab large color="black">

  <v-icon color="grey">mdi-discord</v-icon>
</v-btn>
</a>
</h4> 

<h3><a href="https://open.spotify.com/user/31grxvknsiaavfioejdqbpwzus6i?si=899c39dff9eb499c">
<v-btn icon color="black">

  <v-icon  color = "grey">mdi-spotify</v-icon>
</v-btn>
</a></h3>


  </div>
</template>

<script>
export default {
  
  name: 'helloWorld',
  props: {
    msg: String
  },
   data () {
      return {
        items: [
          {
            src: 'https://cdn.discordapp.com/attachments/919696614824771645/986059718294396968/61875B26-AAD1-4046-A43A-C9C81B2EEEFD.jpg',
          },
  
        ],
      }
    },
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 
</style>
