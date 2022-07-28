<template>
  <nav>
    <h1>金涛大傻逼</h1>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="success">成功按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </nav>
  <router-view />
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less"></style>
