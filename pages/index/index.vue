<template>
	<view class="group_2">
		<image src="./img_warning.png"></image>
		<text class="text_6">该账号因违规无法使用</text>
		<text class="text_7">客服电话：4000331033</text>
	</view>

</template>

<script>
	export default {}
</script>

<style lang="less">
	.group_2 {
		width: 750rpx;
		// height: 1295rpx;
		margin-bottom: 1rpx;
		display: flex;
		flex-direction: column;
		// justify-content: center;
		align-items: center;

		image {
			margin-top: 151rpx;
			width: 128rpx;
			height: 128rpx;
			margin-bottom: 93rpx;
		}


		.text_6 {
			color: rgba(0, 0, 0, 1);
			font-size: 40rpx;
			font-family: PingFangSC-Semibold;
			text-align: left;
			white-space: nowrap;
			line-height: 40rpx;
			font-size: 40rpx;
			font-weight: 600;

		}

		.text_7 {
			font-size: 28rpx;
			white-space: nowrap;
			margin-top: 720rpx;
			font-weight: 500;
			color: #AFAFAF;
			line-height: 40rpx;
			// margin: 720rpx 0 49rpx 0rpx;
		}
	}
</style>
