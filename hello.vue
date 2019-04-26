<template>
  <div class="hello">
    <h1>hello world</h1>
  </div>
</template>

<script>
export default { //导出组件，在其他文件可以通过import引入组件
  name: 'hello',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
.hello {
  color: red;
}
</style>
