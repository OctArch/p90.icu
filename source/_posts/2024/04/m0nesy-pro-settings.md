---
title: m0nesy 鼠标键盘外设、视频设置、准心CFG参数
copyright: BY-NC-SA
date: 2024-04-24 00:00:31
tags:
categories: 选手设置
index_img: /2024/m0nesy-pro-settings/m0.jpg
---

{%player_icon "/2024/m0nesy-pro-settings/player_icon.png" "Ilya “m0NESY” Osipov" %}

以下是 G2 Esports CS2 选手 **Ilya “m0NESY” Osipov** 的画面设置和外设

## 硬件外设

{% player_table

鼠标:"Logitech G Pro X Superlight 2 Black"

键盘:"Logitech G Pro X TKL Keyboard Black (GX-Blue)"

显示器:"ZOWIE GEAR XL2566K"

头戴式耳机:"Logitech G Pro X Headset"

入耳式耳机:"Logitech G333 Black"

鼠标垫:"SteelSeries QcK Heavy"

%}

## 鼠标设置

{% player_mouse DPI=400 Sensitivity=2 Zoom=1 Hz=2000 winSen=6 %}

## 视频设置

### 显示器

{% player_table
分辨率:1280x960
显示比例:4:3
缩放方式:拉伸
亮度:93%
显示模式:全屏
数字震动:50%
%}

### 游戏内设置

{% player_table
提高角色对比度:禁用
等待垂直同步:禁用
多重采样抗锯齿模式:"8x MSAA"
全局阴影质量:非常高
模型/贴图细节:低
贴图过滤模式:"双线性"
光影细节:低
粒子细节:低
环境光遮蔽:高
高动态范围:质量
"FidelityFX 超级分辨率":禁用（最高质量）
"NVIDIA Reflex":禁用
%}

## 鼠标准心

{% player_table
准星类型:经典静态
跟随弹道:否
中心点:否
长度:1
宽度:0
间距:-4
轮廓:关
颜色:自定义
红色:0
绿色:255
蓝色:0
透明度:开
透明值:255
"T 型准星":否
启用准行间距设置:否
开镜宽度:0
%}

准星代码: `CSGO-whESe-jBwvB-JBc4H-i4UFA-FkdVG`

## 持枪视角

{% player_table
FOV:68
"X 轴":2.5
"Y 轴":0
"Z 轴":-1.5
预设坐标:3
手臂晃动:否
%}

```bash
viewmodel_fov 68;
viewmodel_offset_x 2.5;
viewmodel_offset_y 0;
viewmodel_offset_z -1.5;
viewmodel_presetpos 3;
cl_usenewbob false;
```

## Hud

{% player_table
"HUD尺寸":1
"HUD颜色":蓝色
%}

## 雷达

{% player_table
玩家居中:开
雷达旋转:开
随计分板切换形状:开
雷达尺寸:0.91
地图缩放:0.4
%}

```bash
cl_radar_always_centered "1"
cl_radar_icon_scale_min "0.4"
cl_radar_rotate "1"
cl_radar_scale "0.91"
cl_radar_square_with_scoreboard "1"
```
