<template>
    <el-row  class="hello ht-100 wt-100">
        <el-col :span="24" class="ht-100">
            <el-container class="ht-100 wt-100">
                <el-header >
                        header section
                        <HeaderSectionVue></HeaderSectionVue>
                </el-header>
               <el-container>
                    <el-aside width="200px">Aside</el-aside>
                    <el-main>Main</el-main>
                </el-container>
            </el-container>
        </el-col>
    </el-row>
</template>
<script>
import HeaderSectionVue from './HeaderSection.vue'
export default {
  name: 'HomeSection',
  components:{
    HeaderSectionVue
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
.ht-100{
    height: 100%;
}
.wt-100{
    width: 100%;
}
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
  color: #42B983;
}
</style>