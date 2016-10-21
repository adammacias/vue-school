<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'disciplina-single',

  data () {
    return {
    	page: { title: "Disciplina Single" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>