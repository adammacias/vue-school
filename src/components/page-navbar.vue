<template>
  <div>
    <p>Você esta vendo o componente <code>{{ page.title }}</code></p>
  </div>
</template>

<script>
export default {

  name: 'page-navbar',

  data () {
    return {
      page: { title: "Page Navbar" }
    };
  }
};
</script>

<style lang="css" scoped>
</style>