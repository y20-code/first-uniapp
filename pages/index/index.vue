<template>
	<view class="box" hover-class="boxHover">
		<view class="inner">
			内部元素
		</view>
	</view>
	
	<view>-----</view>
	
	<text selectable>text文本标签</text>
	
	<scroll-view scroll-y="true" class="scrollview">
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		<view class="d1">text1</view>
		
	</scroll-view>
</template>

<script setup>

</script>

<style lang="scss">
	.box{
		width:200px;
		height: 200px;
		background-color: #ccc;
	}
	
	.boxHover{
		background-color: red;
	}
	
	.inner{
		width: 20px;
		background-color: green;
	}
	.scrollview{
		width: 80%;
		height: 220px;
		border: 1px solid red;
	}
	
	.d1{
		width: 20px;
		height: 20px;
		background-color: green;
	}
</style>
