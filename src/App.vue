<template>

  <div class="fundo">

    <v-container class="background">

<h1>Feedback Grupos</h1>

      <div class="cards">
        <v-row class="row">

          <v-card
            class="card mx-6"
            max-width="344"
            width="240px"
          >
            <v-img
              height="200px"
              src="./assets/Captura de tela 2024-06-04 202722.png"
              cover
            ></v-img>

            <v-card-title>
              Gustavo Cortezia
            </v-card-title>


            <v-expand-transition>
              <div>
                <v-divider></v-divider>

                <v-card-text>Cortês</v-card-text>
                <v-card-text>Cooperatividade</v-card-text>
                <v-card-text>Liderança</v-card-text>

              </div>
            </v-expand-transition>
          </v-card>


          <v-card
            class="card mx-6"
            max-width="344"
            width="240px"
          >
            <v-img
              height="200px"
              src="./assets/image-bernardo.png"
              cover
            ></v-img>

            <v-card-title>
              Bernardo Dartora
            </v-card-title>


            <v-expand-transition>
              <div>
                <v-divider></v-divider>

                <v-card-text>Humildade</v-card-text>
                <v-card-text>Empenho</v-card-text>
                <v-card-text>Serenidade</v-card-text>

              </div>
            </v-expand-transition>
          </v-card>

                <v-card
            class="card mx-6"
            max-width="344"
            width="240px"
          >
            <v-img
              height="200px"
              src="./assets/379848077_1071135470884813_6306204106673045828_n.jpg"
              cover
            ></v-img>

            <v-card-title>
              Alexsandro da Rocha
            </v-card-title>


            <v-expand-transition>
              <div>
                <v-divider></v-divider>

                <v-card-text>Bom ouvinte</v-card-text>
                <v-card-text>Seriedade</v-card-text>
                <v-card-text>Trabalho em Equipe</v-card-text>

              </div>
            </v-expand-transition>
          </v-card>
                <v-card
            class="card mx-6"
            max-width="344"
            width="240px"
          >
            <v-img
              height="200px"
              src="./assets/daniel-foto.jpg"
              cover
            ></v-img>

            <v-card-title>
              Daniel Gheno
            </v-card-title>


            <v-expand-transition>
              <div>
                <v-divider></v-divider>

                <v-card-text>Criativo</v-card-text>
                <v-card-text>Caridoso</v-card-text>
                <v-card-text>Communicação Assertiva</v-card-text>

              </div>
            </v-expand-transition>
          </v-card>
        </v-row>
              </div>

    </v-container>
  </div>

  </template>

  <style>

  .cards {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 50px; /* Reduzido para um espaçamento mais adequado */
  }

  .fundo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .background {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
  }

  .imagem img {
    max-width: 100%;
    height: auto;
    display: block;
  }

  </style>
