<route lang="json5">
{
  style: {
    navigationBarTitleText: '关于',
  },
}
</route>

<template>
  <view
    class="bg-white overflow-hidden pt-2 px-4"
    :style="{ marginTop: safeAreaInsets?.top + 'px' }"
  >
    <view class="text-center text-3xl mt-8">About</view>
  </view>
</template>

<script lang="ts" setup>
const { safeAreaInsets } = uni.getSystemInfoSync()
</script>
