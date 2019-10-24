<template>
  <div id="content">
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <div class="container col-11">
        <b-navbar-brand href="#">Alaji</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-auto">
            <b-nav-item active right>Accueil</b-nav-item>
            <b-nav-item right>A propos</b-nav-item>
            <b-nav-item right>contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
    <br />
    <div class="content">
      <div class="mx-5">
        <b-jumbotron header="Développeur web" lead>
          <p>
            Le développeur web / la développeuse réalise
            l’ensemble des fonctionnalités techniques d’un
            site ou d'une application web.
            Technicien ou ingénieur, il ou elle conçoit des
            sites sur mesure ou adapte des solutions techniques
            existantes en fonction du projet et de la demande du
            client.
          </p>
          <b-button variant="primary" href="#">en savoir plus</b-button>
        </b-jumbotron>
      </div>

      <div class="row mx-5">
        <b-card-group deck>
          <div class="col-lg-3 col-md-6">
            <b-card
              
              title="HTML"
              :img-src="html5"
              img-alt="Image"
              img-top
              tag="article"
              class="md-3"
              style="text-align:center; height:700px;"
            >
              <b-card-text>
                L'HyperText Markup Language, 
                généralement abrégé HTML, est le langage de balisage 
                conçu pour représenter les pages web. C'est un langage 
                permettant d'écrire de l'hypertexte, d'où son nom.
              </b-card-text>

              <b-button href="#" variant="primary" class="mx-2" style="position:absolute; left:0; bottom: 10px; right:0; margin: auto">Lien vers la doc</b-button>
            </b-card>
          </div>
          <div class="col-lg-3 col-md-6">
            <b-card
              title="Card Title"
              :img-src="css"
              img-alt="Image"
              img-top
              tag="article"
              class="md-3"
              style="text-align:center; height:700px;"
            >
              <b-card-text>
                Les feuilles de style en cascade, 
                généralement appelées CSS de l'anglais 
                Cascading Style Sheets, forment un langage 
                informatique qui décrit la présentation des 
                documents HTML et XML. Les standards définissant 
                CSS sont publiés par le World Wide Web Consortium (W3C).
              </b-card-text>

              <b-button href="#" variant="primary" class="mx-2" style="position:absolute; left:0; bottom: 10px; right:0; margin: auto">Lien vers la doc</b-button>
            </b-card>
          </div>
          <div class="col-lg-3 col-md-6">
            <b-card
              title="Card Title"
              :img-src="js"
              img-alt="Image"
              img-top
              tag="article"
              class="md-3"
              style="text-align:center; height:700px;"
            >
              <b-card-text>
                JavaScript est un langage de programmation 
                de scripts principalement employé dans les pages web 
                interactives mais aussi pour les serveurs2 avec 
                l'utilisation de Node.js.
              </b-card-text>

              <b-button href="#" variant="primary" class="mx-2" style="position:absolute; left:0; bottom: 10px; right:0; margin: auto">Lien vers la doc</b-button>
            </b-card>
          </div>
          <div class="col-lg-3 col-md-6">
            <b-card
              title="Card Title"
              :img-src="php"
              img-alt="Image"
              img-top
              tag="article"
              class="m-6"
              style="text-align:center; padding:25px; height:700px;"
            >
              <b-card-text class="card-text">
                PHP: Hypertext Preprocessor, plus connu sous 
                son sigle PHP, est un langage de programmation libre, 
                principalement utilisé pour produire des pages Web 
                dynamiques via un serveur HTTP, mais pouvant également 
                fonctionner comme n'importe quel langage interprété de 
                façon locale. PHP est un langage impératif orienté objet.
              </b-card-text>

              <b-button href="#" variant="primary" class="mx-2" style="position:absolute; left:0; bottom: 10px; right:0; margin: auto">Lien vers la doc</b-button>
            </b-card>
          </div>
        </b-card-group>
          <br/><br/>
      </div>
    </div>

    <footer class="py-5 bg-dark bottom">
      <div class="container">
        <div class="mx-auto whiter" style="width: 200px;">copyright © Piersanti Dylan</div>
      </div>
    </footer>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

import html5 from "./assets/html5.png";
import css from "./assets/css3.png";
import js from "./assets/js.png";
import php from "./assets/php.svg";

export default {
  name: "app",
  data() {
    return {
      html5,
      css,
      js,
      php
    };
  },
  /* computed: {
    monNom () {
      return this.test(4)
    }
  },
  data () {
    return {
      message: "Test de VueJS avec BootStrap"
    }
  },
  methods: {
    test (num) {
      return `Numuro: ${num}`
    }
  }, */
  components: {
    // HelloWorld
  }
};
</script>

<style>
.whiter {
  color: #fff;
}

.card-text {
  font-size: 14px;
  overflow:auto;
}
</style>
