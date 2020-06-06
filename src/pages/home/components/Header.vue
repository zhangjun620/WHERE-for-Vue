<template>
  <div>
    <div class="header">
      <div class="header-left">
        <div class="iconfont" >&#xe624;</div>
      </div>
      <div class="header-input" >
        <span class="iconfont">&#xe632;</span>
        输入城市景点游玩主题
      </div>
      <div class="header-right" >
       城市
       <span class="iconfont arrow-icon">&#xe64a;</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    display: flex
    line-height: .86rem
    background: $bgColor
    color: #fff
    justify-content: space-around
    .header-left
      text-align: center
      margin-left: .2rem
      width: .64rem
    .header-input
      width: 100%
      height: .64rem
      background: #fff
      border-radius: .1rem
      margin-top: .12rem
      padding-left: .2rem
      line-height: .64rem
      margin-left: .2rem
      color: #ccc
    .header-right
      min-width: 1.04rem
      padding: 0 .2rem
      text-align: center
      .arrow-icon
        font-size: .24rem
</style>
