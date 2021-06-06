<template>
    <div class="main">123</div>
    <el-button>测试</el-button>
</template>

<script lang="ts">
export default {
  name: 'index',
  mounted () {
    this.init()
  },
  methods: {
    init () {
      alert('登录')
    }
  }
}
</script>

<style lang="scss" scoped>
  $bg: red;

  .main {
    width: 100px;
    height: 100px;
    background: $bg;
  }
</style>
