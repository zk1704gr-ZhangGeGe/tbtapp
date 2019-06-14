<template>
	<view class="content">
		<image class="tbtlogo" src="../../static/imgs/tbtlogo.png"></image>
		<view class="lg">
			<text class="text">+86</text>
			<input class="photel" type="text" placeholder="请输入手机号码" v-model="photel" @keyup="sr" />
		</view>
		<view class="yzm">
			<input class="yzm1" type="text" placeholder="请输入验证码" v-model="yzm"  />
			<text class="cxhq">{{cxhq}}</text>
		</view>
		<view class="yzmdlan">
			<text class="text1" @click="hqyzm" :style="{'color': hqyzmancolor}">{{yzmdlan}}</text>
		</view>
		<view class="view1">
			<text class="text2" @click="login1">账号密码登录</text>
			<view class="view2">
				<view class="qq">
					<image class="qqlogo" src="../../static/imgs/QQlogo.png"></image>
				</view>
				<view class="weixin">
					<image class="weixinlogo" src="../../static/imgs/weixinlogo.png"></image>
				</view>
				<view class="weibo">
					<image class="weibologo" src="../../static/imgs/weibologo.png"></image>
				</view>
			</view>
		</view>
		<view class="view3">
			<text class="text3">登录代表您已同意</text>
			<text class="text4">土巴兔用户协议</text>
			<text class="text3">﹑</text>
			<text class="text4">隐私证策</text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
		    return {
				cxhq:'',
				yzmdlan:'获取验证码',
				hqyzmancolor:'rgb(149,149,151)',
				yzm:'123',
				photel:'1763350157'
        	}	
			
		},
		mounted() {
			
		},
		methods:{
			login1(){
				uni.navigateTo({
					url: 'login1'
				});
			},
			sr(){
				if(this.photel.length==11){
					this.hqyzmancolor='rgb(35,199,126)';
				}
			},
			hqyzm(){
				if(this.photel.length==11||this.photel!=''){
					this.yzmdlan='登录';
					this.cxhq='重新获取';
				}
			}
		},
		onNavigationBarButtonTap(){  
			uni.navigateTo({
				url: 'register'
			});	
		}
	}
</script>

<style>
	@import url("../../static/css/login.css");
</style>
