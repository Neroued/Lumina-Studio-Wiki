---
title: Lumina Studio
description: 基于物理校准的多色FDM色彩系统
published: true
date: 2026-04-09T00:02:48.220Z
tags: 
editor: markdown
dateCreated: 2026-03-22T11:57:26.463Z
---

# **Lumina Studio**
## 项目介绍
Lumina-layers在2026年1月开发并且完全开源发布在github上面的软件，lumina为了简化用户使用hueforge/flatforge等其他软件学习门槛过高或需要使用指定要求的耗材的问题，基于物理校准使用了穷举法和简化穷举法来获得实际打印颜色，目前的模式并未带来任何颜色理论计算（未来可能会在2.0的高级功能中推出基于颜色/td值等的颜色计算玩法），目前只是打印-拍摄-提取颜色-根据提取的颜色映射堆叠配方-打印（这像是一种颜色匹配功能，就像是你在autoforge和CMYK Lithophane那样会默认给你匹配一些颜色的功能一样，所以受此启发）
**Lumina-layers is a piece of software developed in January 2026 and released as fully open source on GitHub.Lumina was created to lower the steep learning curve associated with tools like HueForge and FlatForge, as well as to avoid the need for specialized filaments required by those applications.Using physical calibration, it employs exhaustive search and simplified exhaustive methods to determine actual printed colors.The current version does not involve any color-theory-based calculations (such features based on color models, TD values, etc., may be added as advanced functions in version 2.0).At present, the workflow simply consists of: print → photograph → extract color → map stacking recipes based on extracted colors → print.This functions like a color-matching feature, similar to the automatic color-matching behavior found in AutoForge and CMYK Lithophane, which served as the inspiration for this approach.**
> 在开发过程中为了方便用户，自研开发了一款开源的高精度位图转SVG的工具并且会在未来的2.0版本集成在软件内部。During development, an in-house, open-source, high-precision bitmap-to-SVG converter was created for user convenience and will be integrated into the software in the upcoming 2.0 release.
svg tool： https://github.com/Neroued/neroued_vectorizer
{.is-info}

我们积极的和很多耗材厂家进行沟通，在不影响耗材厂家生产的情况下，使用现有的耗材进行打印色卡校准，意思是不会要求任何厂家强行生产特定透光率和颜色的耗材，在这个基础上我们咨询一些厂家的意见，厂家提供现有颜色的耗材，开发组去使用这些耗材打印对应的颜色的色卡，并且通过精校拍摄，来得到最准的色卡预设。同时也支持用户自行分享自己的使用的色卡预设
**We have maintained active communication with numerous filament manufacturers.Without disrupting their existing production processes, we use their off-the-shelf filaments for print color calibration.This means we do not require manufacturers to produce special filaments with customized light transmission rates or specific colors.
Based on this principle, we have consulted with manufacturers, who provide filaments in their existing standard colors.Our development team then uses these filaments to print corresponding color charts, which are captured with precisely calibrated photography to generate the most accurate color presets.
Additionally, users are supported to freely share their own color presets for the filaments they use.**
> **lumina的主旨就是，开源开放，合作共创<BR>The core philosophy of Lumina is open source, open collaboration, and co-creation.。**
{.is-success}

## 更多功能
### 颜色模式 Color Modes
2/4/5/6/8色
### 生成模式 Generation Modes
高保真模式/像素模式/svg模式
High-fidelity mode / Pixel mode / SVG mode
### 其他功能 Other Features
支持自定义色卡和校准颜色功能 Custom color card and color calibration functions
支持调节生成颜色的数量 Adjust the number of generated colors.
支持抠图功能 image cutout / background removal
支持背板独立 Independent backplate
支持描边 Outline
支持添加透明层 Add transparent layer
支持掐丝珐琅模式 wiry enamel(cloisonné enamel)
支持生成预览后替换图中颜色 Replace colors in the image

### 高级功能
支持颜色配方查询功能 Color Formula Search
支持合并色卡功能 Merge color card function