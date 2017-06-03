# 自己动手打造在线Markdown编辑器

## 适合哪些人学习
1. 使用过Markdown
2. 对前端开发有一定的基础知识

## 开发步骤
> 首先来参考一下成熟的Markdown编辑器的效果--目前大部分的都是采用实时编辑预览的模式，在左边进行Markdown写作，在右边就可以实时的看到显示出来的效果。

![示例图片](https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=4052986824,1432795445&fm=26&gp=0.jpg)

### 参照上图我们来分解一下我们要做的事情
1. 实现两个窗口，两个窗口均分页面大小；
2. 左窗口设置为可编辑区域，右窗口可以实时显示第一个窗口里面输入的内容；
3. 将左窗口里面输入的内容通过Markdown语法解析器解析为HTML之后显示在由窗口；


## 实现效果

![实现效果](http://upload-images.jianshu.io/upload_images/4385018-d33a7e0d796814cf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/440)
