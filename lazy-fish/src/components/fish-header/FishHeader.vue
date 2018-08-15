<template>
  <div class="fish-header">
    <img src="./images/二维码.png" class="scan-icon" alt="">
    <div class="search-wrapper">
      <img src="./images/search.png" class="search-icon" alt="">
      <input class="search-input" placeholder="搜索宝贝/鱼塘/用户" type="text"/>
    </div>
    <img src="./images/分类.png" class="category-icon" alt="">
  </div>
</template>

<script>
  export default {
    name: 'FishHeader'
  }
</script>

<style lang="stylus" scoped>
  @import '../../common/stylus/variables.styl';
  .fish-header
    width 100%
    height 56px
    background-color $theme-color
    display flex
    align-items center
    position fixed
    left 0
    top 0
    right 0
    .scan-icon, .category-icon
      width 22.5px
      height 22.5px
      margin 0 15px
    .search-wrapper
      flex 1
      position relative
      .search-icon
        width 22px
        height 22px
        position absolute
        top 6px
        left 5px
      .search-input
        width 86%
        height 30px
        border-radius 5px
        outline none
        border none
        padding-left 35px
</style>