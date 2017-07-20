<template>
  <div id="app">
    <h3>原始资料</h3>
    <el-input
      type="textarea"
      :rows="2"
      placeholder="请输入内容"
      v-model="textarea">
    </el-input>

    <h3>操作</h3>
    <el-button>扫描</el-button>

    <h3>原始码</h3>
    <el-input placeholder="原始码1"></el-input>
    <el-input placeholder="原始码2"></el-input>
    <el-input placeholder="原始码3"></el-input>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      textarea: ''
    }
  },
  methods: {
    find () {}
  }
}
</script>

<style>
#app {
  width: 960px;
  margin: 0 auto;
}
</style>
