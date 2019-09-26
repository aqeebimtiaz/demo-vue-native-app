<template>
  <view class="container">
    <text class="text-color-primary">My Vue Native App</text>
    <text class="text-color-secondary">Aqeeb's first code</text>
    <text-input
      class="text-input-container"
      placeholder="Type here to translate!"
      v-model="textContent"
    />
    <text class="text-container">{{textContent}}</text>
  </view>
</template>

<script>
export default {
  data: function() {
    return {
      textContent: ""
    };
  }
};
</script>

<style>
.container {
  background-color: rgb(78, 235, 148);
  align-items: center;
  justify-content: center;
  flex: 1;
}
.text-color-primary {
  color: blue;
}
.text-color-secondary{
  color: lightslategrey;
}

.text-container {
  color: blue;
  padding: 2;
  font-size: 22;
}
.text-input-container {
  width: 300;
  height: 40;
  font-size: 22;
  border-color: whitesmoke;
}
</style>
