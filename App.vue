<template>
  <view class="container">
    <SampleSdk msg="xpx-vue-native-tutorial"/>
  </view>
</template>


<script>
import SampleSdk from './components/sample-sdk/SampleSdk'

export default {
  components: {
    SampleSdk
  }
}
</script>

<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: blue;
}


</style>


