<template>
  <div class="login-container">
    <!-- 导航栏 -->
    <van-nav-bar title="登录" />
    <!-- 导航栏 -->
    <!-- 登录表单 -->
    <van-form @submit="onSubmit">
      <van-field name="用户名" placeholder="请输入手机号" />
      <van-field type="password" name="密码" placeholder="请输入验证码" />
      <div style="margin: 16px">
        <van-button round block type="info" native-type="submit"
          >提交</van-button
        >
      </div>
    </van-form>
    <!-- 登录表单 -->
  </div>
</template>

<script>
export default {
  name: "ToutiaoMIndex",

  data () {
    return {};
  },

  mounted () {},

  methods: {
    onSubmit (values) {
      console.log("submit", values);
    },
  },
};
</script>

<style lang="less">
</style>
