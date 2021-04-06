<template>
  <div class="www">
    <h1>歪比巴卜</h1>
    <h2>0.0</h2>
    <h3>(--)</h3>
    <div class="aaa">
      <h4>lalalalalalal</h4>
    </div>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>

<style lang="stylus">
.www {
  width: 500px;
  height: 500px;
  border: 2px solid blue;
  text-align: center;
}

h1 {
  color: red;
}

h2 {
  color: yellow;
}

.aaa {
  width: 200px;
  height: 200px;
  background: #ccc;
  margin: 0 150px;

  &:hover {
    background: blue;
  }
}
</style>