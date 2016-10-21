<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'page-footer',

  data () {
    return {
    	page: { title: "Page Footer" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>