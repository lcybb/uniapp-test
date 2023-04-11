<template>
  <view class="flex justify-center items-center flex-col">
    {{ title }}
  </view>
</template>

<script setup lang="ts">
const title = ref("second");
// const title2 = $ref('hello2');
</script>

<style lang="scss">
.text-area {
  display: flex;
  justify-content: center;
}
</style>
