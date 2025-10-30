<template>
  <div class="sign-in">
    <h2>签到</h2>
    <button @click="handleSignIn">立即签到</button>
    <p v-if="signedIn">签到成功！</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      signedIn: false
    }
  },
  methods: {
    handleSignIn() {
      // 此处可接入后端接口
      this.signedIn = true;
    }
  }
}
</script>

<style scoped>
.sign-in {
  text-align: center;
  margin-top: 50px;
}
</style>
