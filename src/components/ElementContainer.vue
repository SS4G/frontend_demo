<template>
    <div class="common-layout">
      <el-container >
        <el-aside width="200px">Aside</el-aside>
        <el-container>
          <el-container>
            <el-header>Header</el-header>
            <el-main>Main</el-main>
            <el-footer>Footer</el-footer>
          </el-container>
        </el-container>
      </el-container>
    </div>
</template>

<script lang="ts" setup>

</script>

<style scoped> 
.el-container {
    height: 100vh;
    width: 100vw;
}
.el-header {
    background-color: aqua;
    height: 20%;
}

.el-main {
    background-color: rgb(25, 0, 255);
    height: 70%;
}

.el-footer {
    background-color: rgb(0, 255, 60);
    height: 10%;
}

.el-aside {
    background-color: rgb(255, 0, 144);
    width: 20%;
}

</style>