<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'aluno-single',

  data () {
    return {
    	page: { title: "Aluno Single" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>