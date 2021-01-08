<template>
  <div>
    <Toolbar />
    <nuxt />
  </div>
</template>
<style>
body {
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
</style>
<script>
import Toolbar from '~/components/toolbar.vue'
export default {
  components: {
    Toolbar,
  },
}
</script>
