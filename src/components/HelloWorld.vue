<template>
  <div class="hello-world">
    <div>{{ msg }}</div>
    <div>
      <el-button type="primary">主要按钮</el-button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped>
.hello-world{
  box-sizing: border-box;
  padding: 50px;
}
</style>
