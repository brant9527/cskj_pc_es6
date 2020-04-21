<template>
  <div class="header">
    <div class="content">
      <div><img src="~/assets/img/logo.png"
             alt=""
             srcset=""></div>
      <div class="word">为出国旅游购物提供一条龙服务!</div>
    </div>
  </div>
</template>
<script >
</script>
<style lang="scss" scoped>
.header {
  height: 80px;
  width: 100%;
  line-height: 80px;
  background-color: #fff;
  .content {
    width: 1300px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    img {
      margin: 30px;
      width: 100px;
    }
  }
  .word {
    font-family: PingFangSC-Medium;
    font-size: 14px;
  }
}
</style>
