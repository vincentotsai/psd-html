# PSD-HTML
> #### 掌握切图的基本流程
> #### 加深对HTML标签及css规范的理解
> #### 考虑浏览器兼容性

## 1. 切图的基本流程

安装和使用[Adobe Photoshop CC 2015](http://jingyan.baidu.com/article/0320e2c1ca4c091b87507ba7.html)。

拿到PSD设计稿，从整体到局部进行审视（头、尾、公共部分有哪些、列表元素）。怎么布局，用哪些标签实现，细节跟设计师确认。

切图：移动工具选中元素所在图层，在“图层”出右键设为“智能对象”，Ctrl+c Ctrl+v （注意：使用像素单位） Ctrl+v 后图层就单独复制出来了。Ctrl+s保存为JPG png GIF都fine。

## 2. 列出HTML结构

设计HTML结构，先列出主干。视情况用HTML5标签语义化。定义class ID时做到合理，如定义public-header要比header好。

！fontcolor要在a标签上写