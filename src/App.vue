<template>
  <div id="app">
    <SignIn />
  </div>
</template>

<script>
import SignIn from './components/SignIn.vue'
export default {
  components: {
    SignIn
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
