<template>
  <div id="app">
    <!-- <el-header>skiresortInformation</el-header> -->
    <el-main>
      <!-- 記述しておくことでviewファイルが埋め込まれる（他のview画面に切り替わってくれる） -->
      <router-view/>
    </el-main>
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
