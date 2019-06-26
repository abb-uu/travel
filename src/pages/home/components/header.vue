<template>
  <div class="header">
    <div class="header-left">
      <i class="fa fa-angle-left"></i>
    </div>
    <div class="header-input">
      <i class="fa fa-search"></i> 输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <i class="fa fa-caret-down"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<style lang="less" scoped>
@import '~styles/varibles.less';

.header {
  line-height: 0.86rem;
  display: flex;
  background: #00bcd4;
  color: #fff;
  .header-left {
    float: left;
    width: 0.64rem;
    font-size: 0.5rem;
    text-align: center;
  }
  .header-input {
    flex: 1;
    background: #fff;
    height: 0.64rem;
    line-height: 0.64rem;
    color: #ccc;
    padding-left: 0.2rem;
    margin-top: 0.12rem;
    border-radius: 0.1rem;
  }
  .header-right {
    width: 1.24rem;
    float: right;
    text-align: center;
  }
}
</style>

