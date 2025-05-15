<script setup>
import page from '../mds/md.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center" class="image-container">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <h3>Framework</h3>
        <el-image 
          src="/model/framework.png" 
          fit="contain"
          alt="Framework"
        />
      </el-col>
    </el-row>
    <el-row justify="center">
        <el-col :xs="24" :sm="22" :md="18" :lg="16" :xl="16">
            <page />
        </el-col>
    </el-row>

  </div>
</template>

<style>
h3 {
  text-align: center;
}
</style>