<template>
  <div>
    <Header></Header>
  </div>
</template>
<style>
.home {
  display: flex;
  max-width: 1280px;
}
</style>
<script>
import Header from '~/components/header/main.vue'
export default {
  components: {
    Header,
  },
}
</script>
