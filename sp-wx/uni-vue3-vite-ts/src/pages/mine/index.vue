
<template>
  <view class="container mine">
    <image class="avator" :src="avator"></image>
  </view>
</template>
<script lang="ts" >
export default {
  name: "user",
  components: {},
  props: {},
  data() {
    return {
      avator: '/static/logo.png'
    }
  },
  computed: {},
  methods: {},
  watch: {},

  // 页面周期函数--监听页面加载
  onLoad() {},
  // 页面周期函数--监听页面初次渲染完成
  onReady() {},
  // 页面周期函数--监听页面显示(not-nvue)
  onShow() {},
  // 页面周期函数--监听页面隐藏
  onHide() {},
  // 页面周期函数--监听页面卸载
  onUnload() {},
  // 页面处理函数--监听用户下拉动作
  // onPullDownRefresh() { uni.stopPullDownRefresh(); },
  // 页面处理函数--监听用户上拉触底
  // onReachBottom() {},
  // 页面处理函数--监听页面滚动(not-nvue)
  // onPageScroll(event) {},
  // 页面处理函数--用户点击右上角分享
  // onShareAppMessage(options) {},
  onTabItemTap(args: any) {
    console.log(args);
  }
}
</script>

<style scoped>
.mine{
  margin-top: 20rpx;
  margin-bottom: 20rpx;
}
.avator{
  width: 160rpx;
  height: 160rpx;
  border-radius: 50%;
}
</style>