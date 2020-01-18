<template>
  <header class="header">
    <el-row type="flex" justify="space-between" class="main">
      <!-- logo -->
      <div class="logo">
        <nuxt-link to="/">
          <img
            src="http://xjc.hnpinxun.com//uploads/logo/20191218/ac8b72c538e6c6d9de860ae38c38dc04.png"
            alt
          />
        </nuxt-link>
      </div>

      <!-- 菜单栏 -->
      <el-row type="flex" class="navs">
        <nuxt-link to="/">首页</nuxt-link>
        <nuxt-link to="/work">工作动态</nuxt-link>
        <nuxt-link to="/news">统战要闻</nuxt-link>
        <nuxt-link to="/hot">热门活动</nuxt-link>
        <nuxt-link to="/contactUs">联系我们</nuxt-link>
        <nuxt-link to="/whereof">关于新联会</nuxt-link>
      </el-row>
    </el-row>
  </header>
</template>hot

<script>
export default {};
</script>

<style lang="less" scoped>
.header {
  height: 90px;
  line-height: 90px;
  background-color: #f28b2e;
  box-sizing: border-box;

  .main {
    width: 1200px;
    margin: 0 auto;
    .logo {
      margin-top: 15px;
      height: 60px;
      width: 60px;
      img {
        display: block;
        width: 100%;
      }
    }
    .navs {
      margin: 0 20px;
      flex: 1;

      a {
        display: block;
        padding: 0 30px;
        height: 80px;
        box-sizing: border-box;
        color: #fff;

        &:hover,
        &:focus,
        &:active {
          border-bottom: 5px #fff solid;
          color: #fff;
        }
      }

      /deep/ .nuxt-link-exact-active {
        // background: #409eff;
        border-bottom: 5px #fff solid;
        color: #fff !important;
      }
    }
  }
}
</style>