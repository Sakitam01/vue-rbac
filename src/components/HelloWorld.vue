<template>
  <div>
    <el-button type="primary">主要按钮</el-button>
  </div>
</template>

<script>
import Vue from "vue";
import { Button } from "element-ui";
Vue.use(Button);

export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<style scoped>
</style>
