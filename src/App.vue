<template>

  <div class="fundo">

    <v-container class="background">

      <div class="imagem mt-15">
        <img class="mt-15" src="./assets/fundo.jpg" alt="">
      </div>

      <div class="cards">
        <v-card
          class="ma-10"
          width="500px"
          subtitle="- cortês - cooperatividade - liderança"
          title="Gustavo Cortezia"
          link
        ></v-card>

        <v-card
          class="ma-10"
          width="500px"
          subtitle="- humildade
    - empenho
    - serenidade"
          title="Bernardo Dartora"
          link
        ></v-card>

        <v-card
          class="ma-10"
          width="500px"
          subtitle="- bom ouvinte
    - seriedade
    - trabalho em equipe"
          title="Alexsandro da Rocha"
          link
        ></v-card>

        <v-card
          class="ma-10"
          width="500px"
          subtitle="- criativo
    - caridoso
    - comunicação assertiva"
          title="Daniel Gheno"
          link
        ></v-card>
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
