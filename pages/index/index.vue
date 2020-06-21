<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<view class="text-area animated rollIn " >
			<button @tap="test()" type="primary">页面主操作 Normal</button>
		</view>
		<view>
			<text class="title">
					<i class="iconfont icon-pinglun2"></i>
				{{title1}}
			</text>
		</view>
		<view>
			<text class="title">
					<i class="iconfont icon-pinglun2"></i>
				{{title2}}
			</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '社区交友',
				title1: '社区交友1',
				title2: '社区交友2',
				title3: '社区交友3',
				
			}
		},
		onLoad() {

		},
		methods: {
			test() {
				console.log('ok')
			}
		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
		width: 200rpx;
		height: 200rpx;
		border:1px solid #007AFF;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
