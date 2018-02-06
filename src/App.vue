<template>
  
    <!-- <img src="./assets/logo.png"> -->
    <!-- <HelloWorld/> -->
      <v-app light>
        <!-- <v-toolbar class="white">
          <v-toolbar-title>
            Wise Code

          </v-toolbar-title>
        </v-toolbar> -->
        <v-content>
          <section>
            <v-parallax src="/static/pc.jpg" height="600">
              <v-layout column align-center justify-center class="white--text">
                <!-- <div>
                <v-card class="my-3" hover>
                  <v-card-media src="/static/guidoban.jpg" alt="Vuetify.js" height="200"></v-card-media>
                  <v-card-text>
                    <h1 class="mb-2 display-1 text-xs-center">Parallax Template</h1>
                    <div class="subheading mb-3 text-xs-center">Powered by Vuetify</div>
                  </v-card-text>
                  <v-card-actions>
                    <v-btn class="blue lighten-2 mt-5" dark large href="/pre-made-themes">
                      Get Started
                    </v-btn>
                  </v-card-actions>
                </v-card>
                </div> -->
                <img src="static/logo.png" >
                <h1 class="white--text mb-2 display-1 text-xs-center">Wise Codes</h1>
                <div class="subheading mb-3 text-xs-center">You Imagine, we code</div>
                  <v-btn
                  class="blue lighten-2 mt-5"
                  dark
                  large
                  href="/pre-made-themes"
                  >
                  Venha Conhecer-nos
                  </v-btn>
              </v-layout>
            </v-parallax>
          </section>
          <section>
            <v-layout  
            column
            wrap
            class="my-5"
            align-center>


              <v-flex xs12 sm4 class="my-3">
                  <div class="text-xs-center">
                  <h2 class="headline">Nossos Serviços</h2>
                  <span class="subheading">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis, consequuntur! Repellat consequatur eum in quibusdam perspiciatis illo, neque, perferendis quia repudiandae error distinctio repellendus impedit? Incidunt tempore odit eos atque.
                  </span>
                  </div>
              </v-flex>


            </v-layout>
          </section>
      </v-content>
    </v-app>
  
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
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
    /* margin-top: 60px; */

    

 }
 .headline{
		color: #303030;
		font-size: 28px;
		font-weight: 700;
		text-transform: uppercase;
	}	
	/* .white--text{
    text-transform: uppercase;
  } */
	.subheading{
		font-size: 14px;
    font-family: Roboto,Helvetica,Arial,sans-serif;
		line-height: 22px;
		font-weight: 300;
		letter-spacing: 0;
	} 
	
</style>
