<template>
	<view class="content">
        <image class="logo" src="../../static/logo.png"></image>
		<view>
            <text class="title">{{title}}</text>
<<<<<<< HEAD
=======
			<text class="content">{{soft1721}}</text>
>>>>>>> 75838bbff53b51870390cd7385166a4e3be71fc6
        </view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello',
				home:'soft1721'
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
		text-align: center;
		height: 400upx;
	}
    .logo{
        height: 200upx;
        width: 200upx;
        margin-top: 200upx;
    }
	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
