<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'page-main',

  data () {
    return {
    	page: { title: "Page Main" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>