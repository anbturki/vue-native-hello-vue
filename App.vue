<template>
  <view class="container">
    <image :style="{width: 100, height: 100}" :source="{uri: 'https://vuejs.org/images/logo.png'}"/>
    <text class="text-color-primary size-35">Hello 100k ⭐️</text>
    <text class="text-color-primary size-25">My First Vue Native App</text>
  </view>
</template>
 
<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: #64b587;
}
.size-35 {
  font-size: 35px;
}
.size-25 {
  font-size: 25px;
}
</style>
