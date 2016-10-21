<template>
	<div>
		<p>Você esta vendo o componente <code>{{ page.title }}</code></p>
	</div>
</template>

<script>
export default {

  name: 'page-header',

  data () {
    return {
    	page: { title: "Page Header" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>