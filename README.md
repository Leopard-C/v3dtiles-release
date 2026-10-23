![logo](./assets/logo/v3dtiles-logo-transparent_320.png)

English | [简体中文](./README_zh-CN.md)

<div>
  <a href="https://github.com/Leopard-C/v3dtiles-release/releases">
    <img
      alt="Windows"
      src="https://img.shields.io/badge/-Windows-blue?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB0PSIxNzI2MzA1OTcxMDA2IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjE1NDgiIHdpZHRoPSIxMjgiIGhlaWdodD0iMTI4Ij48cGF0aCBkPSJNNTI3LjI3NTU1MTYxIDk2Ljk3MTAzMDEzdjM3My45OTIxMDY2N2g0OTQuNTEzNjE5NzVWMTUuMDI2NzU3NTN6TTUyNy4yNzU1NTE2MSA5MjguMzIzNTA4MTVsNDk0LjUxMzYxOTc1IDgwLjUyMDI4MDQ5di00NTUuNjc3NDcxNjFoLTQ5NC41MTM2MTk3NXpNNC42NzA0NTEzNiA0NzAuODMzNjgyOTdINDIyLjY3Njg1OTI1VjExMC41NjM2ODE5N2wtNDE4LjAwNjQwNzg5IDY5LjI1Nzc5NzUzek00LjY3MDQ1MTM2IDg0Ni43Njc1OTcwM0w0MjIuNjc2ODU5MjUgOTE0Ljg2MDMxMDEzVjU1My4xNjYzMTcwM0g0LjY3MDQ1MTM2eiIgcC1pZD0iMTU0OSIgZmlsbD0iI2ZmZmZmZiI+PC9wYXRoPjwvc3ZnPg=="
    />
  </a>
  <a href="https://github.com/Leopard-C/v3dtiles-release/releases">
    <img
      alt="Linux"
      src="https://img.shields.io/badge/-Linux-yellow?style=flat-square&logo=linux&logoColor=white"
    />
  </a>
</div>

A software that supports vector data to 3DTiles, oblique photogrammetry (osgb) model to 3DTiles, oblique model clipping, point cloud to 3DTiles, Gaussian splatting (3DGS) to 3DTiles, remote sensing image tiling, terrain tiling and general model tiling.

Small in size, fast in processing.

+ **GUI** - Provides a WebGUI for visual operation (`http://127.0.0.1:7760`), also accessible from other devices on the LAN via IP.
+ **API** - Provides a set of APIs, which can be integrated into business systems to automate tiling.
+ **AI** - Provides MCP service and SKILL\.md, which can be integrated into agents such as Workbuddy and Claude Code.


## Site

+ Official Website：https://v3dtiles.top


## Documentation

+ User Manual: [Feishu Docs - V3DTILES Software User Manual](https://v3dtiles.top/doc)

+ API Documentation: [Apifox Shared Doc - V3DTILES API Doc](https://v3dtiles.apifox.cn)


## Main Features

+ Tiling Project Management
  + Convert vector data (shp, gdb, gpkg, pg, etc.) to 3DTiles, mainly for generating building white models
  + Convert oblique photogrammetry (osgb) data to 3DTiles
  + Oblique model clipping (precise clipping by polygon extent)
  + Point cloud to 3DTiles
  + Gaussian splatting (3DGS) to 3DTiles
  + Tile images in XYZ or TMS format
  + Terrain data tiling (quantized-mesh-1.0)
  + General model tiling
+ Tiling Task Management
  + Running tasks
  + Completed tasks
+ API Integration​ (Create API Key, integrate with business systems, and automate tiling)
+ MCP Service & SKILL Skills (complete tiling through natural language conversation)
+ Statistical Analysis
+ Service Distribution
  + Single file/folder
  + 3DTiles
  + Terrain service
  + XYZ/TMS image service
+ 3D Visualization
  + Layer management
  + Scene management
  + Place name search
  + Measurement tools
  + Weather simulation
  + Scene lighting
  + Terrain processing
+ System Settings
  + HTTP server configuration
  + IP blacklist/whitelist
  + Input/output directory permission configuration
  + Network proxy

## END