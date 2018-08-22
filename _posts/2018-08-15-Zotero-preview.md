---
title: 追求完美！这款插件让Zotero具备文献预览功能！
date: 2018-08-15 13:55:00
categories:
- 文献管理
tags:
- Zotero
typora-root-url: ../../iseex.github.io
---



假定你是一个Zotero用户，现在问你这样一个问题：“你眼中的Zotero最大的缺点在哪？（特别是相对于Endnote）”



相信很多初学者的答案是：Zotero没有文献预览功能。

确实，在不安装任何插件的情况下，如果想要在Zotero中阅读某个文献，需要该文献条目，然后会在默认的PDF阅读软件中打开，如果想在一堆文献中查找一篇文献（不记得文献内容的情况下），我们必须一一打开每篇文献查看，这会导致PDF阅读软件出现一排密集的标签页。由于PDF阅读软件往往不能秒速打开文件，这种方式势必会影响文献的查找效率，特别是文献很多的情况下。再者，如果不及时关闭不需要的标签页，打开PDF很多时，PDF阅读软件很容易崩溃。所以，这种糟糕的阅读体现肯定不是任何Zotero用户希望的，特别是习惯了Endnote在右侧区域实时预览文献的用户。

那么，有没有什么办法解决上述问题呢？答案是：有。

Zotero作为一款如此受欢迎的开源文献管理软件，广大的开发者们肯定也考虑到了上述问题，并因此开发了好用的插件来武装Zotero，让其具备文献预览功能。

这款插件就是quicklook，下面具体介绍其使用方法。

访问quicklook的[Github链接](https://github.com/mronkko/ZoteroQuickLook#zoteroquicklook)可查看quicklook插件在`Windows`、`Mac`和`Linux`上的使用方法，[访问](https://github.com/mronkko/ZoteroQuickLook/releases)可下载quicklook插件（.xpi格式）。

> 这里补充下quicklook的设计思想。使用过Mac电脑的都知道，在Mac上按空格键可快速预览文件，该功能大大提高了效率，深受欢迎。quiklook正是想让Windows等其他操作系统也具备该功能。

由于`Windows`电脑暂时不在身边，下面就以在`Mac`上安装quicklook为例就行介绍。

1. 在上面给出的quicklook下载链接下载用于Mac的quicklook插件，如下图所示。  


   ![](/assets/images/posts/zotero/pdf-preview01.jpg)

2. 打开Zotero，tools->add-ons，打开插件安装界面，安装上面下载的zoteroquicklook.xpi，安装完如下图所示。


   ![](/assets/images/posts/zotero/pdf-preview02.jpg)

3. 到这里配置工作就搞定了，很简单吧。下面就是具体使用方法了。一旦安装了quicklook，在Zotero中选定一个文献条目，按下空格键，就能快速甚至极速打开文献，在弹出的预览窗口中可以翻页、放大查看，再按下空格键即可快速关闭预览窗口。如果配合上下箭头键，就能通过键盘在一堆文献中快速查找到需要的文献。此处需要注意的是，如果选定文献条目并按下Enter键，则是用Mac自带的预览软件打开文献。

   所以可以发现，这里的逻辑在于：quicklook打开和关闭非常迅速，占用内存很小，极大地提高了使用体验，逼近实时预览的效果。关注**猫Q学术派公众号**可观看我上传的具体使用效果的视频。

到这里，在`Mac`上使用quicklook便介绍完了，是不是很简单。不过需要强调的是，在`Windows`上的配置方法有些不同，除了安装quicklook插件外，还需要配以一款quicklook.exe的软件，大家可以自行摸索。

`Mac`和`Windows`上配置quicklook的所需的插件我已经从Github上下载下来，[点击这里](https://pan.baidu.com/s/1xc8yRtO11dVWsX7xSBjgxQ )可下载，密码：bbwf。

> 更多内容可移步微信公众号“猫Q学术派”