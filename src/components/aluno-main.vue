<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'aluno-main',

  data () {
    return {
    	page: { title: "Aluno Main" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>