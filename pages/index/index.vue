<template>
	<view class="container">

		<view class="intro">本项目已包含uni ui组件，无需import和注册，可直接使用。在代码区键入字母u，即可通过代码助手列出所有可用组件。光标置于组件名称处按F1，即可查看组件文档。</view>
		<text class="intro">详见：</text>
		<view>{{test}}</view>
		<uni-link :href="href" :text="href"></uni-link>
		<view></view>
	</view>
</template>

<script setup>
	// export default {
	// 	data() {
	// 		return {
	// 			href: 'https://uniapp.dcloud.io/component/README?id=uniui'
	// 		}
	// 	},
	// 	methods: {

	// 	}
	// }
	import { ref } from "vue"
	const test = ref("qqq")
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>