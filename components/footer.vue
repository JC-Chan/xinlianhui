<template>
  <div class="footer-wrapper">
    <el-row class="info-list">
      <el-col :span="12" class="left">
        <p>地址: 涧西区蓬莱路2号B区毕昇园10号楼</p>
      </el-col>
      <el-col :span="12" class="right">
        <p>技术支持: 河南品讯网络科技有限公司</p>
        <p>备案: 豫ICP备125462586-1号</p>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.footer-wrapper {
  height: 90px;
//   padding: 10px 0 20px 0;
  padding: 15px;
  background-color: #323232;
  color: #fff;
  .info-list {
    width: 1200px;
    margin: auto;
    font-size: 14px;

    .right {
        p{
            margin-bottom: 10px;
        }
    }
  }
}
</style>