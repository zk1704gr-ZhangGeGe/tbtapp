<template>
	<view class="content">
		<view class="ssl">
			<input class="mSearch-input-box" type="text" placeholder="周口 ▾  | 🛒10秒装修报价" v-model="keyword" />
			<text class="sousuo">搜索</text>
		</view>
		<wSwiper></wSwiper>
		<view class="szzsz">
			<image src="../../static/imgs/suanbaojia.jpg" class="sbj"></image>
			<image src="../../static/imgs/zhaosheji.jpg" class="zsj"></image>
			<image src="../../static/imgs/zhuangxiugongsi.jpg" class="zxgs"></image>
			<image src="../../static/imgs/shenhebaojia.jpg" class="shbj"></image>
			<image src="../../static/imgs/zhuangxiufenqi.jpg" class="zxfq"></image><br>
			<text class="text1">算报价</text>
			<text class="text2">找设计</text>
			<text class="text3">装修公司</text>
			<text class="text4">审核报价</text>
			<text class="text5">装修分期</text>
		</view>
		<view class="sxx">
			<image src="../../static/imgs/shaijiazhengji.jpg" class="shaijiazhengji"></image>
			<image src="../../static/imgs/xiaoguotu.jpg" class="xiaoguotu"></image>
			<image src="../../static/imgs/xuezhuangxiu.jpg" class="xuezhuangxiu"></image>
		</view>
		<view class="sjwdj">
			<image src="../../static/imgs/shejiwodejia.jpg" class="shejiwodejia"></image>
			<text class="szj">设置我的家 开启个性化推荐</text>
			<text class="t">﹥</text>
		</view>
		<fenduanqi></fenduanqi>
	</view>
</template>

<script>
	import fenduanqi from '@/pages/home/fenduanqi.vue';
	import wSwiper from '../../components/wlp-swiper-banner/wlp-swiper-banner.vue';
	export default {
		components: {wSwiper,fenduanqi},
		data() {
		    return {
				keyword: ""
        	}	
		},
		mounted() {

		},
		methods: {
			
		}
	}
</script>

<style>
	@import url("../../static/css/index.css");
</style>
