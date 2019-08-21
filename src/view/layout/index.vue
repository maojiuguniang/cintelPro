<template>
  <el-container class="conStyle">
    <el-header class="headerStyle">
        <navTitle></navTitle>
        <navMenu></navMenu>
    </el-header>
    <!--中间内容-->
    <el-main>

    </el-main>
  </el-container>
</template>

<script>
    import navTitle from './components/navTitle'
    import navMenu from './components/navMenu'

    export default {
        name: 'layout',
        components: {
            navTitle,navMenu
        }
    }
</script>
<style>
  .headerStyle{
    height: 80px !important;
    background: #002762;
    color: #fff;
  }

</style>