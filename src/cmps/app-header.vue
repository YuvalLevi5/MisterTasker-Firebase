<template>
  <header class="header-wrapper ">
    <div  class="main-header main-layout-container">
      <div class="">
        <h1 @click="goHome" class="logo">
          <span class="clr-teal">Mister</span>Tasker
        </h1>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: 'AppHeader',
  components: {},
  data() {
    return {}
  },
  created() { },
  methods: {
    goHome() {
      console.log('run')
      this.$router.push('/')
    },
  },
  computed: {},
  unmounted() { },
}
</script>
<style>
</style>
