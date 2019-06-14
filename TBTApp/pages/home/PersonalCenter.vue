<template>
	<view class="content">
		<view class="head">
			<view @click="logo">
				<image class="headlogo" src="../../static/imgs/tbtdenglulogo.jpg"></image>
				<text class="headtext">登录土巴兔</text>
			</view>
			<image class="lingqutubi" src="../../static/imgs/lingqutubi.jpg"></image>
			<view class="head2">
				<text class="sltext1">0</text>
				<text class="sltext2">0</text>
				<text class="sltext2">0</text>
				<text class="sltext2">0</text><br>
				<text class="text1">发布</text>
				<text class="text2">收藏</text>
				<text class="text3">关注</text>
				<text class="text4">粉丝</text>
			</view>
		</view>
		<view class="neirong">
			<text class="myhome">我的家</text>
			<view class="ljxszsfw6">
				<image class="ljxszsfw" src="../../static/imgs/ljxszsfw.jpg"></image>
			</view>
			<view class="n1">
				<text class="yylf">预约量房</text>
				<text class="sg">|</text>
				<text class="yylf">免费设计</text>
				<text class="sg">|</text>
				<text class="yylf">装修报价</text>
			</view>
		</view>
		<view class="neirong">
			<text class="myhome">常用工具</text>
			<view class="ljxszsfw61">
				<image class="cygj" src="../../static/imgs/qwdz.jpg"></image>
				<image class="cygj" src="../../static/imgs/lfbg.jpg"></image>
				<image class="cygj" src="../../static/imgs/qianbaotubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/youhuiquantubiao.jpg"></image><br>
				<text class="text661">全屋定制</text>
				<text class="text662">量房报告</text>
				<text class="text663">钱包</text>
				<text class="text664">优惠券</text><br>
				<image class="cygj" src="../../static/imgs/lipintubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/zhuangxiujizhangtubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/jisuanqitubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/huanglitubiao.jpg"></image><br>
				<text class="text665">礼品</text>
				<text class="text666">装修记账</text>
				<text class="text667">计算器</text>
				<text class="text668">黄历</text>
			</view>
		</view>
		<view class="neirong1">
			<text class="myhome">第三方服务</text>
			<view class="ljxszsfw61">
				<image class="cygj" src="../../static/imgs/jiajvshangchengtubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/jinrongfuwutubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/yingwanyuanxianjintubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/huafeifangongtubiao.jpg"></image><br>
				<text class="text441">家具商城</text>
				<text class="text442">金融服务</text>
				<text class="text443">赢万元现金</text>
				<text class="text444">装修反工</text><br>
				<image class="cygj" src="../../static/imgs/shaituzhengjitubiao.jpg"></image>
				<image class="cygj" src="../../static/imgs/yusuanbaojiatubiao.jpg"></image><br>
				<text class="text445">晒图征集</text>
				<text class="text446">预算报价</text>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
		    return {
			
        	}	
			
		},
		mounted() {
			
		},
		methods:{
			logo(){
				uni.navigateTo({
					url: 'login',
				})	
			}
		}
	}
</script>

<style>
	@import url("../../static/css/PersonalCenter.css");
</style>
