<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: 'kcolauncher',
    methods: {
      goBack() {
        window.history.length > 1 ? this.$router.go(-1) : this.$router.push('/')
      }
    }
  }
</script>

<style>
  /* CSS */
</style>
