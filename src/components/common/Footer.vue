<template>
  <center>
    <div style="position: absolute;right: 7%;bottom: 10%;">
      <el-tooltip class="item" effect="dark" content="返回顶层" placement="left-start">
        <el-button size="medium" @click="goTop()" icon="el-icon-arrow-up" circle></el-button>
      </el-tooltip>
      <br><br>
      <el-tooltip class="item" effect="dark" content="刷新" placement="left-start">
        <el-button size="medium" @click="goTop()" icon="el-icon-refresh-right" circle></el-button>
      </el-tooltip>
      <br><br>
      <a href="https://jq.qq.com/?_wv=1027&k=2giDHjln">
        <el-tooltip class="item" effect="dark" content="问题反馈QQ群" placement="left-start">
          <el-button size="medium"  @click="gokefu()" icon="el-icon-position" circle></el-button>
        </el-tooltip>
      </a>
    </div>
    <div class="footer" style="margin-top: 90px;margin-bottom: 0px">
        <hr />
        <p>
          <span><a href="">关于我们</a></span>
          <span><a href="">招聘启示</a></span>
<!--          <i class="el-icon-delete"></i>-->
          <span><a href="https://muxixiaowo-my.sharepoint.com/personal/yc_muxixiaowo_ltd/_layouts/15/onedrive.aspx">yc@muxixiaowo.ltd</a></span>
          <span><a href="https://jq.qq.com/?_wv=1027&k=2giDHjln">QQ:1994158249@qq.com<img src="../../assets/img/2.png" width="36" height="36"></a></span>
        </p>

      <p><span>公司地址：江苏省雨花台三江学院</span></p>
      <p><span>Copyright © 2020-2021</span> <span>蔡连强</span></p>
    </div>
  </center>
</template>
<script>
  export default {
    data() {
      return {
        collapse: false,
        fullscreen: false,
        name: 'admin',
        message: 2
      }
    },
    methods:{
      //前往页面头部
      goTop() {
        location.reload();
      },
      //前往客服
      // gokefu() {
      //   location.reload();//刷新页面
      // },
    }
  }
</script>
<style scoped>
  .footer {
    width: 100%;
    height: 160px;
  }
</style>
