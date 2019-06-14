<template>
	<view class="content">
		<image class="tbtlogo" src="../../static/imgs/tbtlogo.png"></image>
		<view class="zm">
				<input class="username" type="text" placeholder="请输入手机/账号/邮箱" v-model="username" />
				<input class="password" type="text" placeholder="请输入密码" v-model="password" />
				<text class="wjmm">忘记密码</text>
		</view>
		<text class="dl">登录</text>
		<view class="view1">
			<text class="text2" @click="login">手机号验证码登录</text>
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
				username:'',
				password:''
        	}	
		},
		mounted() {
			
		},
		methods:{
			login(){
				uni.navigateTo({
					url: 'login'
				});	
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
	@import url("../../static/css/login1.css");
</style>
