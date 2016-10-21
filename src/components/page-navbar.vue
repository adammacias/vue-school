<template>
  <div id="page-navbar">
    <nav class="navbar navbar-inverse">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" v-on:click="toggleNavbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Vue School</a>
        </div>
        <div id="navbar" class="collapse navbar-collapse" :class="{ in: isOpenNavbar }">
          <ul class="nav navbar-nav">
            <li><a href="#">Principal</a></li>
            <li><a href="#">Disciplinas</a></li>
            <li><a href="#">Alunos</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {

  name: 'page-navbar',

  data () {
    return {
    	isOpenNavbar: false
    };
  },

  methods: {
  	toggleNavbar () {
  		this.isOpenNavbar = !this.isOpenNavbar
  	}
  }
};
</script>

<style scoped>
  .navbar {
    border-radius: 0!important;
  }
</style>