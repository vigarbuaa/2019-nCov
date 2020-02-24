<template>
  <div class="header">
  <div class="header-left">
    邮件
  </div>
  <div class="header-logo">
    <div class="logo">
    <!-- <img src="a"></img> -->
      今日头条
    </div>
  </div>
  <div class="header-right">
  搜索
  </div>
  </div>
</template>

<script>

export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
.header
  height:.88rem
  line-height: .88rem
  background-color: #d43d3d
  color:#fff
.header-left
    float:left
    margin-left:.1rem
    height:.86rem
.header-logo
    position:absolute
    margin-left:2.7rem
    width:2.5rem
    .box
      width:3rem
      float:left
    .logo
      font-size : 0.6rem

  .header-right
    float:right
    margin-right:.1rem
    height:.86rem

</style>
