<template>
  <v-container  text-xs-center fluid ma-0 pa-0 >
      <v-flex xs12 ma-0 pa-0 hidden-sm-and-down>
        <video style="
        position: fixed;
        right: 0;
        bottom: 0;
        min-width: 100%;
        min-height: 100%;
        overflow: hidden;"
        src="https://res.cloudinary.com/dylevfpbl/video/upload/v1551060213/donelygunn/crowd.mp4" autoplay muted loop/>
      </v-flex>
      <v-flex class="hidden-sm-and-down intro" xs12 style="position:relative;height:101vh;">
         <v-flex class="title" xs8 offset-xs2 pa-4>
         <div class="display-4 white--text text-xs-center" >
           Designing the Future
         </div>
         <br>
         <div class="text-xs-center">
           <v-btn flat class="buttonOpt"><router-link to="/about">About</router-link></v-btn>
           <v-btn flat class="buttonOpt"><a href="">Thoughts</a></v-btn>
         </div>
       </v-flex>
</v-flex>
  </v-container>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'home',
  components: {

  }
}
</script>
<style scoped>
a{
  text-decoration: none;
  color:black;
}
.title{
  margin: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: rgb(169,169,169,.9);
  /* border-radius: 3%; */
}
.buttonOpt {
  color:  black;
  font-size: 1.4rem;
}
</style>
