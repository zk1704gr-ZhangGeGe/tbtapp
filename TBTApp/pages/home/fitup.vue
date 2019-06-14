<template>
		<view class="content">
				<view class="ssl">
					<input class="mSearch-input-box" type="text" placeholder="搜索装修公司" v-model="keyword" />
					<text class="sousuo">搜索</text>
				</view>
				<view class="zqsj">
					<image src="../../static/imgs/zhuangqitehui.jpg" class="zqth"></image>
					<image src="../../static/imgs/quanwudingzhi.jpg" class="qwdz"></image>
					<image src="../../static/imgs/shangmenliangfang.jpg" class="wmlf"></image>
					<image src="../../static/imgs/jiajvshangcheng.jpg" class="jvsc"></image><br>
					<text class="text1">装企特惠</text>
					<text class="text2">全屋定制</text>
					<text class="text3">上门量房</text>
					<text class="text4">家居商城</text>
				</view>
					<wSwiper1></wSwiper1>
			<view class="xuanze">
				<text class="zonghe">综合 ▾</text>
				<text class="qugd">区域 ▾</text>
				<text class="qugd">更多 ▾</text>
			</view>
			<view class="neirong">
				<view class="nr1">
					<image src="../../static/imgs/shenqiunanfanglogo.jpg" class="sqnfzslogo"></image>
					<text class="sqnf">沈丘南方装饰</text>
					<text class="jvli">46.8km</text>
					<text class="anli">案例：17</text>
					<text class="gongdi">工地：4</text>
					<image src="../../static/imgs/neirong1.jpg" class="neirong1img"></image>
				</view>
				<view class="nr1">
					<image src="../../static/imgs/shenqiunanfanglogo.jpg" class="sqnfzslogo"></image>
					<text class="sqnf">沈丘南方装饰</text>
					<text class="jvli">46.8km</text>
					<text class="anli">案例：17</text>
					<text class="gongdi">工地：4</text>
					<image src="../../static/imgs/neirong1.jpg" class="neirong1img"></image>
				</view>
				<view class="nr1">
					<image src="../../static/imgs/shenqiunanfanglogo.jpg" class="sqnfzslogo"></image>
					<text class="sqnf">沈丘南方装饰</text>
					<text class="jvli">46.8km</text>
					<text class="anli">案例：17</text>
					<text class="gongdi">工地：4</text>
					<image src="../../static/imgs/neirong1.jpg" class="neirong1img"></image>
				</view>
				<view class="nr1">
					<image src="../../static/imgs/shenqiunanfanglogo.jpg" class="sqnfzslogo"></image>
					<text class="sqnf">沈丘南方装饰</text>
					<text class="jvli">46.8km</text>
					<text class="anli">案例：17</text>
					<text class="gongdi">工地：4</text>
					<image src="../../static/imgs/neirong1.jpg" class="neirong1img"></image>
				</view>
				<view class="nr1">
					<image src="../../static/imgs/shenqiunanfanglogo.jpg" class="sqnfzslogo"></image>
					<text class="sqnf">沈丘南方装饰</text>
					<text class="jvli">46.8km</text>
					<text class="anli">案例：17</text>
					<text class="gongdi">工地：4</text>
					<image src="../../static/imgs/neirong1.jpg" class="neirong1img"></image>
				</view>
				<view class="nr1">
					<image src="../../static/imgs/shenqiunanfanglogo.jpg" class="sqnfzslogo"></image>
					<text class="sqnf">沈丘南方装饰</text>
					<text class="jvli">46.8km</text>
					<text class="anli">案例：17</text>
					<text class="gongdi">工地：4</text>
					<image src="../../static/imgs/neirong1.jpg" class="neirong1img"></image>
				</view>
			</view>
		</view>
</template>

<script>
	import wSwiper1 from '../../components/wlp-swiper-banner1/wlp-swiper-banner1.vue';
	export default {
		components: {wSwiper1},
		data() {
		    return {
			
        	}	
			
		},
		mounted() {
			
		},
		methods:{
			
		}
	}
</script>

<style>
	@import url("../../static/css/zhuangxiu.css");
</style>
