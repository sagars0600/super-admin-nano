<template>

  <el-row class="ht-100 wt-100">
    <el-col :span="24" class="ht-100">
<el-container style="height: 500px; border: 1px solid #eee">
    <el-aside width="200px" style="background-color: rgb(238, 241, 246)">
        aside section
    </el-aside>
    
    <el-container>
      <el-header style="text-align: right; font-size: 12px">
            header section
      </el-header>
      
      <el-main>
            main section
      </el-main>
    </el-container>
  </el-container>
</el-col>
</el-row>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
