<template>
	<view class="articlebox">
		<view class="pic">
			<img mode="aspectFill" src="../../static/logo.png" alt="" srcset="">
		</view>
		<view class="text">
			<view class="title">title</view>
			<view class="info">
				<text>作者</text>
				<text>999</text>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		name:"articlebox",
		data() {
			return {
				
			};
		}
	}
</script>

<style scoped>
	
	.articlebox{
		display: flex;
	}
	.articlebox .pic{
		width: 230rpx;
		height: 160rpx;
	}
	.pic image{
		height: 100%;
		width: 100%;
	}
	.articlebox .text{
		border: 1px solid red;
		flex: 1;
	}
</style>