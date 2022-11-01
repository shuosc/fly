# 上海大学溯源手册(SHUFly)

![size](https://img.shields.io/github/repo-size/shuosc/fly)

## 意见反馈
- 【腾讯文档】上海大学溯源手册意见征集📝- https://docs.qq.com/sheet/DTkF5V3VJT3lZTkhX?tab=BB08J2

---

![image1](https://user-images.githubusercontent.com/100942238/195527273-014e4aab-6603-4a27-a996-3aaea9d8b0a5.jpg)

---

## 如何使用

### 在线网站

访问 https://shuosc.github.io/fly/

点击右上角 分类 或 标签 以快速查看

### 本地部署

```bash
git clone https://github.com/shuosc/fly.git --depth=1
cd fly
git submodule update --init --recursive  # 拉取 Hugo 主题
# 确保已安装 Hugo
hugo serve
```

---

## 如何贡献

支持**使用本名或昵称**投稿

内容可按照 `time-name-major-how-where.md` 模板准备，[点此预览](https://shuosc.github.io/fly/posts/time-name-major-how-where/)

为方便不熟悉计算机操作者，提供以下两种方式：

### GitHub 提交

- Fork 本项目
- 添加并编辑 Markdown 文件
  - `hugo new posts/文件名.md` 或直接复制 `content/posts/` 目录下现有文件并修改
  - 注意文件名规范
  - 在开头添加 category/tag，方便快速检索不同专业，保研/考研/出国/工作等去向，以及 CN/US/CA/UK/SG 等上岸地区 
  - 若有条件可在本地部署预览网页效果
- 发起 Pull Request

### 邮箱投递

发送电子邮件至 shuosc@duck.com 标题请注明「投稿/修改-姓名-专业-去向」并附上微信号
