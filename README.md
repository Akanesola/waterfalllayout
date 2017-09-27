# 批量快速自动对图片进行排版处理程序

> 基于一款jQuery可自定义高度图片瀑布流代码（支持自定义高度以及用URL地址直接添加图片的jQuery瀑布流特效）。
下载及预览地址：
> http://sc.chinaz.com/jiaoben/150712571420.htm

## 操作流程：
1、在picture文件夹下，放入要处理的图片。（建议文件名使用数字由大到小命名）
2、修改index.html文件中`<div class='grid-item'><img src='picture/1.jpg'></div>`中的图片文件名（已设置好20张图片处理，单没有测试图片，请下载自行测试），刷新页面后使用网页截图工具保存效果图，当然，您还可以修改背景或图片显示样式后进行截图保存。


## 简单的样式修改：

背景色修改：
`style.css  51行   修改：background-color: #f5f5f5;`

图片添加阴影：
`style.css  149行  添加：box-shadow: 0 0 20px 2px #ccc;`


## PS：
做过一些功能上的修改，内容如下：
1、隐藏上下功能选项
`style.css   82行`

2、关闭点击图片移除功能
`websit.js   45行  `



