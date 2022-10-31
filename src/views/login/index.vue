<template>
  <div>
    <el-button @click="submitLogin">点击登录</el-button>
  </div>
</template>


<script>
export default {
  data() {
    return {

    }
  },
  methods: {
    submitLogin() {
      this.$router.push('/test');
    }
  }
}
</script>