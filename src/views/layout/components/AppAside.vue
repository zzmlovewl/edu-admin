<template>
  <div class="app-aside">
    <el-menu
      default-active="1"
      class="el-menu-vertical-demo"
      background-color="#545c64"
      text-color="#fff"
      active-text-color="#ffd04b"
      unique-opened
      router
    >
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>权限管理</span>
        </template>
        <el-menu-item index="/role"
          ><i class="el-icon-setting"></i>角色管理</el-menu-item
        >
        <el-menu-item index="/menu"
          ><i class="el-icon-setting"></i>菜单管理</el-menu-item
        >
        <el-menu-item index="/resource"
          ><i class="el-icon-setting"></i>资源列表</el-menu-item
        >
      </el-submenu>
      <el-menu-item index="/course">
        <i class="el-icon-menu"></i>
        <span slot="title">课程管理</span>
      </el-menu-item>
      <el-menu-item index="/user">
        <i class="el-icon-document"></i>
        <span slot="title">用户管理</span>
      </el-menu-item>
      <el-submenu index="4">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>广告管理</span>
        </template>
        <el-menu-item index="/advert"
          ><i class="el-icon-document"></i>广告列表</el-menu-item
        >
        <el-menu-item index="/advert-space"
          ><i class="el-icon-document"></i>广告位列表</el-menu-item
        >
      </el-submenu>
    </el-menu>
  </div>
</template>
<script>
export default {
  name: 'AppAside'
}
</script>
<style lang="scss" scoped>
.app-aside {
  height: 100%;
  .el-meun {
    height: 100%;
    border-right: 0 none;
  }
}
</style>
