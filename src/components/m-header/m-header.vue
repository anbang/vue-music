<template>
  <div class="m-header">
    <div class="icon"></div>
    <div class="text">muisic name</div>
  </div>
</template>

<script>
  export default{}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~assets/stylus/variable.styl";
  @import "~assets/stylus/mixin.styl";

  .m-header
    position relative
    height 44px;
    text-align center;
    color $color-theme
    border-bottom 1px solid $color-theme-d
    font-size 0
    .icon
      display inline-block
      vertical-align top
      margin-top 6px
      width 30px
      height 32px
      margin-right 9px
      bg-image('logo')
      background-size 30px 32px
    .text
      display:inline-block
      vertical-align top
      line-height 44px
      font-size $font-size-large
    .mine
      position absolute

</style>
