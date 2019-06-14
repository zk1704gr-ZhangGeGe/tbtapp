<template>
	<view class="content">
			<!-- <input type="text" placeholder="请输入账号" v-model="username" />
			<input type="text" placeholder="请输入用户名" v-model="cname" />
			<input :type="flag" placeholder="请输入密码" v-model="password" />
			<image id="eye" :src="eye"  @click='fn'></image>
			<input type="text" placeholder="请输入手机号" v-model="telno" />
			<input type="text" placeholder="请输入邮箱" v-model="email" />
			<view class="view">
				<radio-group @change="gsex">
				<label class="radio"><radio value="男" checked="true" />男</label>
                <label class="radio"><radio value="女"/>女</label>
				</radio-group>
			</view>
			<view class="view">
				<picker @change="bm" :value="index" :range="arr" range-key="compname">
					<view class="uni-input">{{arr[index].compname}}</view>
				</picker>
            </view>
			<button @click="register">确认</button> -->
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
			
		},
		onNavigationBarButtonTap(){  
		uni.navigateTo({
			url: 'login'
		});		  
	}
	}
</script>

<style>
	@import url("../../static/css/register.css");
</style>
