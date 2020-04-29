<template>
  <div class="header">
    <!-- 顶部 -->
    <div class="nav-topbar">
      <!-- 顶部内容 -->
      <div class="container">
        <!-- 顶部左侧菜单 -->
        <div class="topbar-menu">
          <a href="javascript:;">小米商城</a>
          <a href="javascript:;">MUI</a>
          <a href="javascript:;">云服务</a>
          <a href="javascript:;">协议规则</a>
        </div>
        <!-- 顶部右侧用户相关 -->
        <div class="topbar-user">
          <a href="javascript:;">姓名</a>
          <a href="javascript:;">登陆</a>
          <a href="javascript:;">退出</a>
          <a href="javascript:;">我的订单</a>
          <a href="javascript:;" class="my-cart"><span class="icon-cart"></span>购物车</a>
        </div>
      </div>
    </div>
    <div class="nav-header"></div>
  </div>
</template>

<script>
export default {
  name: "nav-header"
};
</script>


<style lang='scss'>
.header {
  .nav-topbar {
    height: 39px;
    line-height: 39px;
    background-color: #333333;
    color: #b0b0b0;
    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      a {
        display: inline-block;
        color: #b0b0b0;
        margin-left: 17px;
      }
      .my-cart{
          width:110px;
          background-color:#FF6600;
          text-align:center;
          color:#ffffff;
          margin-right:0;
          .icon-cart{
            width: 16px;
            height: 12px;
            background-image: url('/imgs/icon-cart-checked.png') no-repeat center;
            background-size: contain;
            margin-right:4px;
          }
      }
    }
  }
}
</style>