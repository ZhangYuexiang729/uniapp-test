<template>
	<view>
		{{text.id}}
	</view>
</template>

<script>
	export default {
		data() {
			return {
				text:{}
			}
		},
		onLoad(e) {
			console.log("页面加载",e)
			this.text = e
		},
		methods: {
		
		}
	}
</script>

<style>

</style>
