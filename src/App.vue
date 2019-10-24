<template>
  <div id="content">
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand href="#">Alaji</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item class="active" right>Accueil</b-nav-item>
          <b-nav-item right>A propos</b-nav-item>
          <b-nav-item right>contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
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
</style>
