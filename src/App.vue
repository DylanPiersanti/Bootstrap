<template>
  <div id="content">
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <div class="container mx-5">
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
  <br/>
    <div class="mx-5">
      <b-jumbotron header="Développeur web" lead="">
        <p>Le développeur web / la développeuse réalise 
          l’ensemble des fonctionnalités techniques d’un 
          site ou d'une application web. 
          Technicien ou ingénieur, il ou elle conçoit des 
          sites sur mesure ou adapte des solutions techniques 
          existantes en fonction du projet et de la demande du 
          client.</p>
        <b-button variant="primary" href="#">en savoir plus</b-button>
      </b-jumbotron>
    </div>

    <footer class="py-5 bg-dark fixed-bottom">
      <div class="container">
        <div class="mx-auto whiter" style="width: 200px;">copyright © Piersanti Dylan</div>
      </div>
    </footer>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "app",
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
</style>
