<template>
<v-container>
  <v-row class="section-divisions">
    <v-spacer></v-spacer>
    <v-col class="col" cols="3">
      <v-img class="company-icon" src="../../public/img/logo-rounded.jpg"></v-img>
      <h3 class="titre-divisions">Entretien de paysage</h3>
      <p class="info-divisions text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tenetur voluptates ad delectus veritatis neque obcaecati cumque voluptatem cupiditate ipsam quisquam aut velit, atque odio omnis molestiae accusamus? Harum, dolorem assumenda?</p>
    </v-col>
    <v-spacer></v-spacer>
    <v-col class="col" cols="3">
      <v-img class="company-icon" src="../../public/img/logo-rounded.jpg"></v-img>
      <h3 class="titre-divisions">Boutique</h3>
      <p class="info-divisions text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tenetur voluptates ad delectus veritatis neque obcaecati cumque voluptatem cupiditate ipsam quisquam aut velit, atque odio omnis molestiae accusamus? Harum, dolorem assumenda?</p>
    </v-col>
    <v-spacer></v-spacer>
    <v-col class="col" cols="3">
      <v-img class="company-icon" src="../../public/img/logo-rounded.jpg"></v-img>
      <h3 class="titre-divisions">Services Professionnels</h3>
      <p class="info-divisions text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tenetur voluptates ad delectus veritatis neque obcaecati cumque voluptatem cupiditate ipsam quisquam aut velit, atque odio omnis molestiae accusamus? Harum, dolorem assumenda?</p>
    </v-col>
    <v-spacer></v-spacer>
    </v-row>
    <v-row class="section-about">
      <h2 class="titre-about">À propos de nous</h2>
      <p class="info-about text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo nam temporibus omnis sunt ullam quisquam praesentium alias doloremque voluptas dignissimos quia magni non, placeat architecto culpa delectus, fuga, necessitatibus vel? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum deserunt ipsa odio reprehenderit officiis, quisquam adipisci! At, magni ullam voluptatibus velit corporis aliquam ipsam consequatur error reiciendis repellendus, dolores soluta! Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iste qui nobis dolorum nemo officiis maxime culpa consequatur, similique ut enim obcaecati vitae harum magnam ab nesciunt ea, atque fugiat consequuntur!</p> 
    </v-row>
    <v-row class="section-moreInfo">
      <v-col cols="4">
        <div class="info-moreInfo1">
          <h3 class="titre-moreInfo">Titre</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure molestias accusantium totam expedita, optio aliquam commodi quidem ex porro perferendis, sunt, sed repellat dicta error numquam accusamus asperiores officiis quia?</p>
        </div>
      </v-col>
      <v-col cols="8">
        <v-img class="image-moreInfo1" src="../../public/img/img1.jpeg"/>
      </v-col>
    </v-row>
    <v-row class="section-moreInfo">
      <v-col cols="8">
        <v-img class="image-moreInfo2" src="../../public/img/img1.jpeg"/>
      </v-col>
      <v-col cols="4">
        <div class="info-moreInfo2">
          <h3 class="titre-moreInfo">Titre</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure molestias accusantium totam expedita, optio aliquam commodi quidem ex porro perferendis, sunt, sed repellat dicta error numquam accusamus asperiores officiis quia?</p>
        </div>
      </v-col>
    </v-row>

</v-container>
</template>

<style>
  .v-container {
    margin: 0;
    padding: 0;
  }
  .titre-divisions {
    margin: 10px;
  }
  .info-vlaue {
    padding: 5px;
    text-align: center;
  }
  .company-icon {
    width: 3vw;
    margin: auto;
  }
  .section-divisions {
    width: 100vw;
    padding: 30px;
    background-color: white;
  }
  .section-about {
    width: 100vw;
    padding: 5vw 15vw 5vw 16vw;
    background-color: rgb(37, 112, 37);
    text-align: justify;
    margin: 5vw 0 5vw 0;
  }
  .section-moreInfo {
    width: 100vw;
    padding: 1vw 15vw 1vw 16vw;
    position: relative;
  }
  .titre-moreInfo {
    color: white;
    font-size: 2vw;
  }
  .image-moreInfo1 {
    width: 700px;
    box-shadow: 5px 5px 5px rgb(164, 164, 164);
    border-radius: 10px;
  }
  .info-moreInfo1 {
    color: white;
    background-color: rgb(23, 23, 136);
    padding: 2.5vw;
    width: 35vw;
    position: absolute;
    right: 50vw;
    z-index: 1;
    margin-top: 3vw;
    border-radius: 10px;
    border: 1px solid white;
    font-size: 1.5vw;
  }
  .image-moreInfo2 {
    width: 700px;
    box-shadow: 5px 5px 5px rgb(164, 164, 164);
    border-radius: 10px;
  }
  .info-moreInfo2 {
    color: white;
    background-color: rgb(23, 23, 136);
    padding: 2.5vw;
    width: 35vw;
    position: absolute;
    left: 50vw;
    z-index: 5;
    margin-top: 3vw;
    border-radius: 10px;
    border: 1px solid white;
    font-size: 1.5vw;
  }

  .titre-about {
    color: white;
    font-size: 3vw;
  }
  .info-about {
    color: white;
  }
</style>