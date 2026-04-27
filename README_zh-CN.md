![logo](./assets/logo/v3dtiles-logo-transparent_320.png)

[English](./README.md) | 简体中文

<div>
  <a href="https://github.com/EcoPasteHub/EcoPaste/releases">
    <img
      alt="Windows"
      src="https://img.shields.io/badge/-Windows-blue?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB0PSIxNzI2MzA1OTcxMDA2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjE1NDgiIHdpZHRoPSIxMjgiIGhlaWdodD0iMTI4Ij48cGF0aCBkPSJNNTI3LjI3NTU1MTYxIDk2Ljk3MTAzMDEzdjM3My45OTIxMDY2N2g0OTQuNTEzNjE5NzVWMTUuMDI2NzU3NTN6TTUyNy4yNzU1NTE2MSA5MjguMzIzNTA4MTVsNDk0LjUxMzYxOTc1IDgwLjUyMDI4MDQ5di00NTUuNjc3NDcxNjFoLTQ5NC41MTM2MTk3NXpNNC42NzA0NTEzNiA0NzAuODMzNjgyOTdINDIyLjY3Njg1OTI1VjExMC41NjM2ODE5N2wtNDE4LjAwNjQwNzg5IDY5LjI1Nzc5NzUzek00LjY3MDQ1MTM2IDg0Ni43Njc1OTcwM0w0MjIuNjc2ODU5MjUgOTE0Ljg2MDMxMDEzVjU1My4xNjYzMTcwM0g0LjY3MDQ1MTM2eiIgcC1pZD0iMTU0OSIgZmlsbD0iI2ZmZmZmZiI+PC9wYXRoPjwvc3ZnPg=="
    />
  </a>
  <a href="https://github.com/EcoPasteHub/EcoPaste/releases">
    <img
      alt="Linux"
      src="https://img.shields.io/badge/-Linux-yellow?style=flat-square&logo=linux&logoColor=white"
    />
  </a>
</div>

一款支持矢量数据转3DTiles、倾斜模型转3DTiles、倾斜模型裁切、点云转3DTiles、遥感影像切片、地形切片的软件。

提供 HTTP 接口，同时内置完善的 WebGUI 页面。

软件体积小，数据处理速度快。


## 网站

软件官网：https://v3dtiles.top


## 文档

用户手册: [飞书云文档 - V3DTILES软件用户手册](https://v3dtiles.top/doc)

API文档: [Apifox分享文档 - V3DTILES API 文档](https://v3dtiles.apifox.cn)


## 主要功能

+ 切片工程管理
  + 矢量数据 (shp, gdb, gpkg, pg 等) 转为3DTiles，主要用于生成房屋白模
  + 倾斜摄影数据转为3DTiles
  + 倾斜模型裁切 (根据多边形范围精确裁切)
  + 点云转3DTiles
  + 遥感影像按照XYZ或TMS格式切片
  + 地形数据切片 (quantized-mesh-1.0)
+ 切片任务管理
  + 执行中任务
  + 已执行任务
+ 统计分析
+ 服务分发
  + 单文件/文件夹
  + 3DTiles
  + 地形服务
  + XYZ/TMS影像服务
+ 三维可视化
  + 图层管理
  + 场景管理
  + 地名搜索
  + 量测工具
  + 天气模拟
  + 场景光照
  + 地形处理
