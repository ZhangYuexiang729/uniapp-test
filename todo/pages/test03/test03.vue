<template>
	<view>
		test03
		<button @click="open">跳转到text02</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			open(){
				uni.switchTab({
					url: '/pages/test02/test02'
				});
			}
		}
	}
</script>

<style>

</style>
