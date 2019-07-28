<template>
  <div id="app">
    <h1>App----</h1>
    <van-button type="default">默认按钮</van-button>
    <div class="test"></div>
    <router-view />
  </div>
</template>

<style lang="less">
.test {
  // 设计稿尺寸为750,除以2作为px值
  width: 700px;
  height: 200px;
  background-color: yellow;
}
</style>
