<template>
  <view class="flex justify-center items-center flex-col">
    <image
      class="h-200rpx w-200rpx mt-200rpx mb-200rpx mx-auto"
      src="./static/logo.png"
    />
    <view class="text-area">
      <text class="text-size-36rpx text-gray-400">{{ title }}</text>
    </view>
    <button @tap="toSecond">to second</button>
  </view>
</template>

<script setup lang="ts">
const title = ref("Hello");
// const title2 = $ref('hello2');

function toSecond() {
  uni.navigateTo({
    url: "./index",
  });
}
</script>

<style lang="scss">
.text-area {
  display: flex;
  justify-content: center;
}
</style>
