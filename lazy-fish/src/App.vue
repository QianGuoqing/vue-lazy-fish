<template>
  <div id="app">
    <fish-header></fish-header>
    <div class="app-main">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
  import FishHeader from './components/fish-header/FishHeader.vue'
  export default {
    name: 'App',
    components: {
      FishHeader
    }
  }
</script>

<style lang="stylus">
  .app-main
    margin-top 56px
</style>
