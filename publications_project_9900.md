---
layout: page
title: 数据仓储管理系统
permalink: /publications/project-9900/
---

# 数据仓储管理系统

这里是数据仓储管理系统项目的一些截图和最终英文报告。

## 截图

![导入截图](/images/projects/9900/add_new.png)

我们允许用户从本地上传文件或直接贴入开源数据库的链接，后端会定期自动进行拉取。

![连线截图](/images/projects/9900/line.png)

数据会自动抓取出关键字（key），然后通过连线的方式与客户指定的结构进行映射。

连线行为会被缓存，支持redo和undo。

映射关系可以作为文件被导出和导入。

![转化截图](/images/projects/9900/success.png)

选择映射转化后后端会将该数据转化为客户所需的键值映射，如果转化出现错误也会在弹窗中显示。

![地图截图](/images/projects/9900/map.png)

在数据库的信息详情中，我们用MapLibreGL JS制作了一个功能，能够将数据库内所有的点都在地图上显示，从而能够直观了解库的内容。

## 报告

- [下载报告 PDF](/images/projects/9900/9900report.pdf)

