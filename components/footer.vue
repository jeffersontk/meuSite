<template>
  <v-footer :absolute="!fixed" app light>
    <span>&copy; {{ new Date().getFullYear() }}</span>
  </v-footer>
</template>

<script>
export default {
  data() {
    return {
      fixed: false,
    }
  },
}
</script>
