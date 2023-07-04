<template>
	<view class="content">
		<image class = "logo" src="https://raw.githubusercontent.com/chewshanyu/fusion/main/FusionETA.png"></image>
		<view>
			<text class="title">{{title}}</text>
			<text class="title">{{title2}}</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'fusioneta.com ',
				title2:  'Bitrix24是一体化的免费管理平台来帮助您实现有效的团队管理和进行销售。Bitrix24为集成到您的企业所有的业务流程管理，提升它们的效率而设计的。'
			}
		},
		onLoad() {

		},
		methods: {

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
		height: 47rpx;
		width: 180rpx;
		margin: 200rpx auto 50rpx auto;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
