<template>
  <div class="navTitle">{{navTitle}}</div>
</template>

<script>
    export default {
        data() {
            return {
                navTitle: '江苏省公安厅通讯网络新型违法犯罪综合打击平台'
            }
        }
    }
</script>
<style>
  .navTitle{
    padding:10px 0;
    font-weight: bold;
  }
  .el-tabs__item{
    color: #fff !important;
  }
  .el-tabs__item.is-active {
    color: #409EFF !important;
  }
</style>


