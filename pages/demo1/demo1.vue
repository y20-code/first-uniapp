<template>
	<view>
		<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000">
			<swiper-item><image src="/static/mzt.avif" aspectFill></image></swiper-item>
			<swiper-item><image src="/static/dlam.avif" aspectFill></image></swiper-item>
			<swiper-item><image src="/static/lbxx.avif" aspectFill></image></swiper-item>
		</swiper>
	</view>
</template>

<script setup>
</script>

<style lang="scss">
	swiper{
		witdh:100vw;
		height: 200px;
		border:1px solid green;
		swiper-item{
			width: 100%;
			height: 100%;
			background-color: pink;
			image{
				width: 100%;
				height: 100%;
			}
		}
	}
	.png{
		width: 100px;
		height: 100px;
	}
</style>
