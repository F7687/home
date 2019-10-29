<template>
  <div class="banner">
    <div class="block">
      <el-carousel height="600px">
        <el-carousel-item v-for="item in img" :key="item">
          <img :src="item" alt="" />
        </el-carousel-item>
      </el-carousel>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      img: [
        "https://i.loli.net/2019/10/30/FTMj74oQ8DaEmSq.jpg",
        "https://i.loli.net/2019/10/30/7JecNTd5LgSbohs.jpg",
        "https://i.loli.net/2019/10/30/hqIM2b1LlKno9HJ.jpg"
      ]
    };
  }
};
</script>
<style lang="less" scoped>
.banner {
  padding-top: 80px;
  width: 100%;
  img {
    width: 100%;
  }
}
/deep/.el-carousel__button {
  width: 20px;
  height: 20px;
  border-radius: 50%;
}
</style>
