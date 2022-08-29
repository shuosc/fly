---
title: "关于上海大学飞跃手册"
date: 2022-08-29T11:04:49+08:00
draft: false
comment: false
lightgallery: true
---

由 [上海大学开源社区](https://github.com/shuosc/) 出品

## 如何使用

### 在线网站

访问 https://shuosc.github.io/fly/

点击右上角 分类 或 标签 以快速查看

### 本地部署

```
git clone https://github.com/shuosc/fly.git --depth=1
git submodule update --init --recursive  # 拉取 Hugo 主题
cd fly
# 确保已安装 Hugo
hugo serve
```

## 如何贡献

支持**使用本名或昵称**投稿

内容可按照 `time-name-major-how-where.md` 中的 Markdown 模板准备

为方便不熟悉计算机操作者，提供以下两种方式：

### GitHub 提交

- Fork 本项目
- 添加并编辑 Markdown 文件
 - `hugo new posts/time-name-major-how-where.md` 或直接复制 `posts/` 目录下现有文件并修改
 - 注意文件名规范
 - 在开头添加 category/tag，方便快速检索不同专业，保研/考研/出国/工作等去向，以及 CN/US/CA/UK/SG 等上岸地区 
 - 若有条件可在本地部署预览网页效果
- 发起 Pull Request

### 邮箱投递

发送电子邮件至 shuosc@duck.com 标题请注明「投稿/修改-姓名-专业-去向」并附上微信号
