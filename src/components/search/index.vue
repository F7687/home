<template>
  <div class="search ">
    <BreadCrumbs>
      <!-- //面包屑 -->
      <div class="sea_bread ct">
        <span>当前位置：</span>
        <a href="#/">双国广告</a>
        <span> ＞ </span>
        <a href="#/search">搜索广告</a>
      </div>
    </BreadCrumbs>
    <!-- 广告信息 -->
    <AdvInformation />
    <span
      ><a
        href="tencent://Message/?Uin=1006722824&amp;websiteName=local.edu.com:8888=&amp;Menu=yes"
        class="btn btn-qq"
        ><img
          border="0"
          src="https://i.loli.net/2019/10/30/n4gHwxmNEOpce7Z.png"
          alt="hello xym!!"
          title="hello xym!!"/></a
    ></span>
  </div>
</template>
<script>
import BreadCrumbs from "./children/BreadCrumbs";
import AdvInformation from "./children/AdvInformation";
export default {
  data() {
    return {};
  },
  components: {
    BreadCrumbs,
    AdvInformation
  }
};
</script>
<style lang="less" scoped>
.search {
  font-weight: 300;
  font-size: 16px !important;
  padding-top: 80px;
}
.sea_bread {
  a:last-child {
    // font-weight: 900;
  }
  a:hover {
    color: cornflowerblue;
  }
}
</style>
