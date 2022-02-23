# 功能说明
该网站可用来测试各平台设备浏览器对于CSS特性的兼容性。

从左至右（或从上往下）功能分别为：

## 第一张卡片：
网站封面图。我分别用 sRGB 和 P3 色域的代码写了这张卡片的背景，如果你用苹果设备与其他设备对比观看，会发现效果不同。
```css
backdrop-filter:
```

## 第二张卡片：
测试浏览器是否支持显示 8px 字号大小。若不支持 8px 字号显示，浏览器会以 10px 字号来显示 8px 字号。
```css
font-size:
```

## 第三张卡片：
测试浏览器或操作系统是否支持显示 900 至 100 多种字重。
```css
Font-weight:
```

## 第四张卡片：
测试浏览器是否支持背景高斯模糊效果。
```css
backdrop-filter:
```
## 第五张卡片：
测试操作系统是否支持亮/暗色切换。
```css
@media (prefers-color-scheme: dark) 
```

## 第六张卡片：
测试设备是否支持 Display P3 色域的图片显示。若支持 Display P3 色域，左右两个半圆的颜色会有些许的不同，左侧的绿色比右侧更鲜艳，若不支持 Display P3 色域，左右两个半圆的颜色则一致。

使用绿色作为对比是因为绿色的 sRGB 与 Display P3 色域范围差别最大。

## 第七张卡片：
测试浏览器是否支持sRGB、Display P3 或 rec2020 色域，若支持，蓝灯亮起，反则不亮灯。
```css
@media (color-gamut: )
```

## 第八张卡片：
以图片格式测试浏览器对 Display P3 与sRGB 色域的兼容性，如果您的浏览器支持 Display P3色域，那么左右两侧的半圆颜色应该会有些许不同。

## 第九张卡片：
字面意思。

<hr>

**使用资源：**
- [SF 符号](https://developer.apple.com/sf-symbols/)
- [Sans Forgetica 字体](https://sansforgetica.rmit.edu.au/)
- [Clip Path 制作工具](https://bennettfeely.com/clippy/)
