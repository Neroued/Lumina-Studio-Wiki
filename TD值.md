---
title: TD值/HEX值分享
description: 
published: true
date: 2026-04-01T17:40:32.473Z
tags: 
editor: markdown
dateCreated: 2026-04-01T17:22:01.393Z
---

# 什么是TD值
什么是TD值？Hueforge给你的答案是：光线照射透过99%光线的距离就是TD值，单位是mm比如一个耗材TD值为0.1那么对应的就是99%光线透过的是0.1mm。
# 为什么共享这个值？
在包括Hueforge，Hicolor，彩色版画生成器等等生成器/软件中，会使用HEX值和TD值，Lumina目前的方案并未直接使用TD值，只是在更多颜色色卡中进行了通用td值的理论排列去重和简化，在校准过程中还未涉及到TD值。但为什么要分享这个值，因为在我们每次打印耗材厂家提供的耗材的时候，我们会顺手把TD值和颜色值进行同步测试，方便其他用户另作他用（需要td值的软件）。这就分享这个值的原因，另一层原因是为了长远发展，如果后面做更多扩展功能，涉及到了td值和hex值的计算，这样就节省了很多时间和精力。


---
## 爱丽兹
| 类型 | 颜色名称 | TD值 | 潘通色号 | HEX色值 |
| ---- | -------- | ---- | -------- | ------- |
| PLA | 白色 | 7.00 | / | #FFFFFF |
| PLA | 黄色 | 6.30 | Pantone 102 C | #fce300 |
| PLA | 橙色 | 5.50 | Pantone 165 C | #ff671f |
| PLA | 红色 | 4.50 | Pantone 187 C | #a6192e |
| PLA | 品红色 | 3.30 | Pantone 239 C | #db3eb1 |
| PLA | 青色 | 2.70 | Pantone 2382 C | #008ad8 |
| PLA | 灰色 | 1.90 | Pantone Cool Gray 8 C | #888b8d |
| PLA | 蓝色 | 1.70 | Pantone 2728 C | #0047bb |
| PLA | 紫色 | 1.60 | Pantone 2102 C | #6558b1 |
| PLA | 深咖色 | 0.60 | Pantone 4975 C | #3f2021 |
| PLA | 金属银 | 0.40 | Pantone 877 C | #8a8d8f |
| PLA | 黑色 | 0.20 | / | #000000 |
| PLA | 墨绿色 | 0.20 | Pantone 7484 C | #00573f |