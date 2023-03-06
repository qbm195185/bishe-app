<template>
	<view class="home">
		<scroll-view scroll-x class="navscroll">
			<view class="item">帖子</view>
			<view class="item">校园圈</view>
			<view class="item">校园咸鱼</view>
			<img src="../../static/search.png" alt="搜素" srcset="" class="search">
		</scroll-view>
		<view class="content">
			<div class="row" v-for="item in 10">
				<articlebox></articlebox>
			</div>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style scoped>
	.navscroll {
		height: 100rpx;
		background-color: aliceblue;
		text-align: center;
	}
	.navscroll .item {
		font-size: 40rpx;
		display: inline-block;
		line-height: 100rpx;
		padding: 0 20rpx;
		color: #333;
	}
	.search{
		position: relative;
		right: 10rpx;
		top: 10rpx;
		/* size: 60rpx; */
	}
	.content{
		padding: 15rpx;
	}
	.content .row{
		border-bottom: 1px dashed #efeeef;
		padding: 10px;
	}
</style>
