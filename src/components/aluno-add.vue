<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'aluno-add',

  data () {
    return {
    	page: { title: "Aluno Add" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>