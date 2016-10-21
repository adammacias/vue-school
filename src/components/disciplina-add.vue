<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'disciplina-add',

  data () {
    return {
    	page: { title: "Disciplina Add" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>