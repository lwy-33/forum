<template>
  <div>
    <el-table
        :data="tableData"
        style="width: 100%">
      <el-table-column
          label="用户编号"
          prop="date"
          width="120">
      </el-table-column>
      <el-table-column
          label="头像"
          prop="name"
          width="120">
      </el-table-column>
      <el-table-column
          label="用户名"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="密码"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="性别"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="电子邮件"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="角色"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="昵称"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="个人简介"
          prop="address"
          width="120">
      </el-table-column>
      <el-table-column
          label="被访问次数"
          prop="address"
          width="120">
      </el-table-column>


    </el-table>


  </div>
</template>

<script>
export default {
  name: "UserManager",
  data() {
    return {

    }
  }
}
</script>

<style scoped>

</style>