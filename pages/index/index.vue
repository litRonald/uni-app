<template>
	<view class="container">
		
		<view>
			<text @click="say">tewte</text>
			<view>{{msg}}</view>
		</view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				href: 'https://uniapp.dcloud.io/component/README?id=uniui',
				msg: ''
			}
		},
		methods: {
			say() {
				this.msg = 'HELLO'
			}
		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
