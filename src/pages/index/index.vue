<template>
  <view class="index">
    <view>JSX</view>
    <JsxComp />
    <view>==========================</view>
    <!-- <view>
      <button>button 2</button>
      <label>label 2</label>
      <picker mode="date">date picker 2</picker>
    </view> -->
  </view>
</template>

<script>
import JsxComp from '../../components/JsxComp'

export default {
  name: 'Index',
  components: {
    JsxComp
  }
}
</script>

<style>
.index {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
