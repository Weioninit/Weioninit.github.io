---
layout: post
category: "read"
title:  "Win10 tensorflow 安装一步到位"
---

# 版本一定要匹配
## 详细版本:

>[Anaconda3 4.2.0](https://repo.continuum.io/archive/)

>[Cudnn v6.0](<https://developer.nvidia.com/>)

>CUDA 8.0

>Tensorflow 1.3.0

## 注意事项：

1. Anaconda3 4.2.0 是默认python3.5， 可以从<https://repo.continuum.io/archive/>直接下载，不需要

    另外配置python版本和创建环境。

2. Tensorflow1.3.0只支持cudnn 6.0以上的版本，所以通过pip install 安装tensorflow最新版，只能配置

    cudnn6.0 ,如果使用较低版本的cudnn，载入时会找不到模块。

