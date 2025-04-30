<script>
export default {
  data() {
    return {
      // Select the first image to display
      image_path: "./my/framework.jpg",
    }
  }
}
</script>

<template>
  <el-row justify="center">
    <el-col :span="24">
      <el-image :src="image_path" fit="cover" />
    </el-col>
  </el-row>
</template>

<style>
/* Optional: Style the image container */
.el-image {
  width: 100%;
  height: auto;
}
</style>