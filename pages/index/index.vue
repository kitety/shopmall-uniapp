<template>
    <view class="index">
        <!-- #ifndef APP -->
        <view class="wx-nav">
            <view class="icon-Magnifier iconfont">
            </view>
            <view class="">
                百年奥莱
            </view>
            <view class="icon-xiaoxi iconfont">
            </view>
        </view>
        <!-- #endif -->



        <view class="f-active-color">
            23232312323
        </view>
        <view class="iconfont icon-lajitong">

        </view>
    </view>
</template>

<script>
    export default {
        data() {
            return {
                title: 'Hello'
            }
        },
        onLoad() {

        },
        methods: {

        }
    }
</script>

<style scoped>
    .wx-nav {
        box-sizing: border-box;
        height: 100upx;
        width: 100%;
        line-height: 100upx;
        display: flex;
        justify-content: space-between;
        padding: 0 8upx;
        /* #ifdef MP-WEIXIN */
        height: 200upx;
        line-height: 200upx;
        /* #endif */
    }
</style>
