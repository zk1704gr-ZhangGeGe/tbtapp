<template>
	<view class="content">
		 <view>
        <uni-segmented-control class="uni-segmented-control" :current="current" :values="items" @clickItem="onClickItem" style-type="text" active-color="#005A5B"></uni-segmented-control>
        <view class="content1">
            <view v-show="current === 0">
				<tuijian></tuijian>
            </view>
            <view v-show="current === 1">
				效果图
            </view>
            <view class="kfa" v-show="current === 2">
                看方案
            </view>
			 <view v-show="current === 3">
				问答
			</view>
			 <view v-show="current === 4">
			    攻略
			</view>
			<view v-show="current === 5">
				日记
			</view>
        </view>
    </view>
		
	</view>
</template>
<script>
	import tuijian from "../FenDuan/Tuijian.vue"
	import uniSegmentedControl from "@/components/uni-segmented-control/uni-segmented-control.vue"
		export default {
			components: {uniSegmentedControl,tuijian},
			data() {
				return {
					items: ['推荐','效果','方案','问答','攻略','日记'],
					current: 0
				}
			},
			methods: {
				onClickItem(index) {
					if (this.current !== index) {
						this.current = index;
					}
				}
			}
		}
</script>

<style>
	/* @import url("../../static/css/fenduanqi.css"); */
</style>
