<template>
  <div id="app">
    <page-navbar></page-navbar>
    <div class="container">
      <page-main></page-main>
      <disciplina-main></disciplina-main>
      <disciplina-add></disciplina-add>
      <disciplina-single></disciplina-single>
      <aluno-main></aluno-main>
      <aluno-add></aluno-add>
      <aluno-single></aluno-single>
    </div>
    <page-footer></page-footer>
  </div>
</template>

<script>
import PageNavbar from './components/page-navbar.vue'
import PageFooter from './components/page-footer.vue'
import PageMain from './components/page-main.vue'
import DisciplinaMain from './components/disciplina-main.vue'
import DisciplinaAdd from './components/disciplina-add.vue'
import DisciplinaSingle from './components/disciplina-single.vue'
import AlunoMain from './components/aluno-main.vue'
import AlunoAdd from './components/aluno-add.vue'
import AlunoSingle from './components/aluno-single.vue'

export default {
  name: 'app',
  components: {
    PageNavbar, PageFooter, PageMain, 
    DisciplinaMain, DisciplinaAdd, DisciplinaSingle,
    AlunoMain, AlunoAdd, AlunoSingle

  },
  data () {
    return {
    }
  }
}
</script>

<style src="./assets/sass/app.scss" lang="sass"></style>
