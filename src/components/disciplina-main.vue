<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'disciplina-main',

  data () {
    return {
    	page: { title: "Disciplina Main" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>