<template>
  <el-container>
    <el-main>
      <el-image
        style="width: 260px; height: 260px"
        src="https://github.com/tamaroning/tamaroning.github.io/blob/gh-pages/src/assets/icon-600px.png?raw=true"
        fit="fill"
      ></el-image>
      <h2>tamaron</h2>
      <p>京都大学 工学部情報学科 B2</p>
      <p>Rustとプログラム解析が好きです</p>

      <h2>Links</h2>
      <el-row :gutter="20">
        <el-col
          ><el-link :underline="false" href="https://twitter.com/tamaroning"
            >Twitter</el-link
          >
          <div class="grid-content bg-purple"></div
        ></el-col>
        <el-col
          ><el-link :underline="false" href="https://github.com/tamaroning"
            >GitHub</el-link
          >
          <div class="grid-content bg-purple"></div
        ></el-col>
        <el-col
          ><el-link :underline="false" href="https://tamaron.hatenablog.com/"
            >HatenaBlog</el-link
          >
          <div class="grid-content bg-purple"></div
        ></el-col>
      </el-row>
    </el-main>
  </el-container>
</template>
