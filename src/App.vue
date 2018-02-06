<template>
    <!-- <img src="./assets/logo.png"> -->
    <!-- <HelloWorld/> -->
      <v-app light>
         <v-toolbar class="white">
          <v-toolbar-title>
            Wise Codes

          </v-toolbar-title>
        </v-toolbar>
        <v-content>
          <section>
            <v-parallax alt="haha" src="static/hero.jpeg" height="600">
              <v-layout column align-center justify-center class="white--text">
                <img src="static/logo1.png" alt="vuetifiy" height="120" >
                <h1 class="white--text mb-2 display-1 text-xs-center">Wise Codes</h1>
                <div class="subheading mb-3 text-xs-center">You Imagine, we code</div>
                  <v-btn
                  class="blue lighten-2 mt-5"
                  dark
                  large

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
                align-center
                >
                <v-flex xs12 sm4 class="my-3">
                  <div class="text-xs-center">
                    <h2 class="headline">Nossos Serviços</h2>
                    <span class="subheading ">
                    Conheça um Pouco do nosso Trabalho
                    </span>
                  </div>
                </v-flex>


                <!-- <div>
               <v-card hover>
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
                <v-flex xs12>
                  <v-container grid-list-xl>
                    <v-layout row wrap align-center>
                      <v-flex xs12 md4>
                        <v-card hover>
                          <v-card-media src="/static/img-web.jpg" alt="Vuetify.js" height="200"></v-card-media>
                          <v-card-text >
                            <h1 class="mb-2 display-1 text-xs-center light-blue--text">Desenvolvimento Web</h1>
                            <div class="subheading mb-3 text-xs-center">Powered by Vuetify</div>
                          </v-card-text>
                          <v-card-actions>

                          </v-card-actions>
                        </v-card>
                      </v-flex>
                      <v-flex xs12 md4>
                        <v-card hover>
                          <v-card-media src="/static/img-mobile.jpg" alt="Vuetify.js" height="200"></v-card-media>
                          <v-card-text>
                            <h1 class="mb-2 display-1 text-xs-center light-blue--text">Desenvolvimento Mobile</h1>
                            <div class="subheading mb-3 text-xs-center">Powered by Vuetify</div>
                          </v-card-text>
                          <v-card-actions>

                          </v-card-actions>
                        </v-card>
                      </v-flex>
                      <v-flex xs12 md4>
                        <v-card hover>
                          <v-card-media src="/static/treino.jpg" alt="Vuetify.js" height="200"></v-card-media>
                          <v-card-text>
                            <h1 class="mb-2 display-1 text-xs-center light-blue--text">Treinamento para Sua Equipe</h1>
                            <div class="subheading mb-3 text-xs-center">Powered by Vuetify</div>
                          </v-card-text>
                          <v-card-actions>

                          </v-card-actions>
                        </v-card>
                      </v-flex>
                    </v-layout>
                  </v-container>
                </v-flex>


              </v-layout>
          </section>

          <section>
            <v-layout
              column
              wrap
              class="my-5"
              align-center
            >
              <v-flex xs12 sm4 class="my-3">
                <div class="text-xs-center">
                  <h2 class="headline">Nossos Produtos</h2>
                  <span class="subheading ">
                     Conheça um Pouco do nosso Trabalho
                    </span>
                </div>
              </v-flex>


              <!-- <div>
             <v-card hover>
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
              <v-flex xs12 sm4>
                <v-card class="my-3" hover>
                  <v-card-media
                    class="white--text"
                    height="190px"
                    src="static/luki.png"
                  >
                    <v-container fill-height fluid>
                      <v-layout fill-height>
                        <v-flex xs12 align-end d-flexbox>
                          <!--<span class="headline">LUKI</span>-->
                        </v-flex>
                      </v-layout>
                    </v-container>
                  </v-card-media>
                  <v-card-text>
                      <div>
                        <!--<span class="grey&#45;&#45;text">Number 10</span><br>-->
                        <span>Um novo jeito de interagir com
                        centros de beleza já está disponível!</span><br>
                        <!--<span>Whitsunday Island, Whitsunday Islands</span>-->
                      </div>
                  </v-card-text>

                  <v-card-actions>

                      <v-btn icon class="red--text">
                        <v-icon medium>fa-twitter</v-icon>
                      </v-btn>
                      <v-btn icon class="light-blue--text">
                        <v-icon medium>fa-instagram</v-icon>
                      </v-btn>
                      <v-btn icon class="blue--text text--darken-4">
                        <v-icon medium>fa-facebook</v-icon>
                      </v-btn>
                      <v-spacer></v-spacer>
                      <v-btn flat class="blue--text"
                             >
                        Saiba Mais
                      </v-btn>

                  </v-card-actions>
                </v-card>
              </v-flex>



            </v-layout>
          </section>
          <section>
            <v-layout
             row
              wrap
              align="center"
            >
                <v-flex xs10 offset-xs1  >
                  <div class="text-xs-center">
                    <h2 class="headline">Nossa Equipe</h2>
                    <span class="subheading">Lorem ipsum dolor sit amet, consectetur adipisicing elit. ibusdam quisquam, reprehenderit rerum similique tempore veritatis? Corporis?</span>
                  </div>
                </v-flex>

              <v-flex xs12>
                <v-container grid-list-xl>
                  <v-layout row wrap align-center>
                    <v-flex xs12 md3>
                      <v-card hover>
                        <v-card-media src="/static/team-member-1.png" alt="Vuetify.js" height="300"></v-card-media>
                        <v-card-text >
                          <h1 class="mb-2 display-1 text-xs-center light-blue--text">Guilherme</h1>
                          <div class="subheading mb-3 text-xs-center">Front-End</div>
                        </v-card-text>
                        <v-card-actions>

                        </v-card-actions>
                      </v-card>
                    </v-flex>
                    <v-flex xs12 md3>
                      <v-card hover>
                        <v-card-media src="/static/team-member-2.png" alt="Vuetify.js"  height="300"></v-card-media>
                        <v-card-text>
                          <h1 class="mb-2 display-1 text-xs-center light-blue--text">Gildasio </h1>
                          <div class="subheading mb-3 text-xs-center">Mobile</div>
                        </v-card-text>
                        <v-card-actions>

                        </v-card-actions>
                      </v-card>
                    </v-flex>
                    <v-flex xs12 md3>
                      <v-card hover>
                        <v-card-media src="/static/team-member-4.png" alt="Vuetify.js" height="300"></v-card-media>
                        <v-card-text>
                          <h1 class="mb-2 display-1 text-xs-center light-blue--text">Pierre</h1>
                          <div class="subheading mb-3 text-xs-center">Dev-ops Back-End</div>
                        </v-card-text>
                        <v-card-actions>

                        </v-card-actions>
                      </v-card>
                    </v-flex>
                    <v-flex xs12 md3>
                      <v-card hover>
                        <v-card-media src="/static/team-member-4.png" alt="Vuetify.js" height="300"></v-card-media>
                        <v-card-text>
                          <h1 class="mb-2 display-1 text-xs-center light-blue--text">Rogerio</h1>
                          <div class="subheading mb-3 text-xs-center">Mobile</div>
                        </v-card-text>
                        <v-card-actions>

                        </v-card-actions>
                      </v-card>
                    </v-flex>
                    <v-flex xs12 md3>
                      <v-card hover>
                        <v-card-media src="/static/team-member-4.png" alt="Vuetify.js" height="300"></v-card-media>
                        <v-card-text>
                          <h1 class="mb-2 display-1 text-xs-center light-blue--text">João Neto</h1>
                          <div class="subheading mb-3 text-xs-center">Mobile Devops</div>
                        </v-card-text>
                        <v-card-actions>

                        </v-card-actions>
                      </v-card>
                    </v-flex>
                  </v-layout>
                </v-container>
              </v-flex>
            </v-layout>
          </section>

          <!-- <section>
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
          </section> -->
      </v-content>
    </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld'

// export default {
  // name: 'App',
  // components: {
  //   HelloWorld
  // }
// }
</script>

<style>
  /* #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  } */
 /* .headline{
		color: #303030;
		font-size: 28px;
		font-weight: 700;
    text-transform: uppercase;
    padding:20px;
  }

	.white--text h1{
    text-transform: uppercase;
  }
  .subheading{
    font-size:14px;
    font-family: Roboto,Helvetica,Arial,sans-serif;
    font-weight: 400;
  }
	.sub{
		font-size: 14px;
    font-family: Roboto,Helvetica,Arial,sans-serif;
		line-height: 22px;
		font-weight: 10;
    letter-spacing: 0;
	}  */

</style>
