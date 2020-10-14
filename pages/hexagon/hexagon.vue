<template>
	<view class="content">
    <view class="item-1">
      <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx"></hexagon>
      <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-color="red"></hexagon>
      <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-color="blue"></hexagon>
    </view>
		<view class="item-2">
		  <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-width="10rpx"></hexagon>
		  <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-color="green"></hexagon>
		  <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-color="#acacac"></hexagon>
		  <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-width="10rpx"></hexagon>
		</view>
    <view class="item-3">
      <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx"></hexagon>
      <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-color="red"></hexagon>
      <hexagon class="hexagon" src="/static/logo.png" mode="aspectFill" size="200rpx" border-color="#acacac"></hexagon>
    </view>
	</view>
</template>

<script>
  import hexagon from '@/components/glory-hexagon/hexagon.vue';
	export default {
    components:{
      hexagon
    },
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
  .content{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
  .item-1{
    display: flex;
  }
  .item-2{
    display: flex;
    margin-top: -50rpx;
  }
  .item-3{
    display: flex;
    margin-top: -50rpx;
  }
  .hexagon{
    margin: 0 4rpx;
  }
</style>
