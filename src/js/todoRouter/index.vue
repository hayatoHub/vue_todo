<template lang="html">
  <div>
    <div class="page-description">
      <p>Todo with Routing of vue-router</p>
    </div>
    <!-- ルーティングの指定したファイルのroutes.js sを表示してくれているところ -->
    <!-- この上の部分はURLが変わっても表示され続ける -->
    <router-view />
  </div>
</template>

<script>
export default {
};
</script>

<style lang="scss" scoped>
.page-description {
  padding: 10px 20px;
  text-align: right;
  p {
    display: inline-block;
    color: #333;
    font-size: 18px;
  }
}
</style>
