<template>
    <view class="content">
        <image class="logo" src="/static/logo.png"></image>
        <view class="text-area">
            <text class="title">{{ title }}</text>
        </view>
    </view>
</template>

<script>
export default {
    data() {
        return {
            title: 'Hello',
        }
    },
    onLoad() {
        console.log(abc)
    },
    methods: {},
}
</script>

<style lang="scss" scoped>
.content {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.logo {
    width: 200rpx;
    height: 200rpx;
    margin: 200rpx auto 50rpx;
}
.text-area {
    display: flex;
    justify-content: center;
}
.title {
    font-size: 36rpx;
    color: #8f8f94;
}
</style>
