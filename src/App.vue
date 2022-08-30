<template>
  <div id="app">
    <app-header />
    <router-view />
  </div>
</template>

<script>
  import appHeader from './cmps/app-header.vue'
  export default {
    created() {
      this.$store.dispatch({type: 'loadTasks'})
    },
    components: {appHeader},
  }
</script>

<style>

</style>
