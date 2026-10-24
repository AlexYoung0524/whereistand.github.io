# 在场 · Where I Stand

> 事情不尽然如此 / Against Easy Answers

**https://whereistand.xyz**

[中文](#中文) · [English](#english)

---

## 中文

这里是博客「在场」的源码。文章写在这个仓库里，push 到 `main` 之后由 GitHub Actions 自动构建，半分钟后出现在网站上。

### 写些什么

这里的文章多半在干同一件事：找一个大家都点头的说法，比如「都一样」「自古以来」「詹姆斯是 GOAT」，把它拆开看看里面装的是什么。拆完不一定有标准答案，但起码能看出来，它不是一整块。

文章分四个栏目：

- **胡思乱想**：从一件小事或一个词出发，想到哪儿算哪儿。
- **小题大作**：一次经历引出来的观察。题是小题，做得大了点。
- **世界赠予我的**：写人，写记忆。
- **北纬59度**：瑞典和欧洲的事。斯德哥尔摩在北纬 59 度，冬天下午三点天就黑了，挺适合在家写字。

大部分文章有中英两个版本，中文是原文。

### 仓库里有什么

```
content/zh-cn/posts/       中文文章
content/en/posts/          英文文章
static/images/posts/       文章配图
hugo.toml                  站点配置
themes/LoveIt/             主题（git submodule）
.github/workflows/         自动部署
```

### 本地预览

```bash
git clone --recursive https://github.com/AlexYoung0524/whereistand.github.io.git
cd whereistand.github.io
hugo server -D
```

需要 [Hugo](https://gohugo.io/) extended 版。打开 http://localhost:1313 就能看到。

### 版权

文章和图片版权归作者所有。想转载，先发邮件打个招呼：jihui.yang0.0@gmail.com

---

## English

This is the source for the blog *Where I Stand* (在场, "being there"). Posts live in this repo. Every push to `main` triggers GitHub Actions, which builds the site and puts it online about thirty seconds later.

### What it's about

Most posts here do the same thing. They take something everyone nods along to, like "it's all the same," "it has been this way since ancient times," or "LeBron is the GOAT," and pull it apart to see what's actually inside. There isn't always a neat answer at the end, but at least it turns out the thing was never one solid piece.

Posts fall into four categories:

- **Wandering Thoughts**: starting from a small thing or a single word and following it wherever it goes.
- **Overthinking**: observations prompted by something I lived through. Small topics, taken a bit too far.
- **Life's Gift**: about people and memories.
- **59° North**: Sweden and Europe. Stockholm sits at 59 degrees north, and in winter it's dark by 3 p.m., which makes for good writing weather.

Most posts come in both Chinese and English. The Chinese is the original.

### What's in the repo

```
content/zh-cn/posts/       Chinese posts
content/en/posts/          English posts
static/images/posts/       Post images
hugo.toml                  Site config
themes/LoveIt/             Theme (git submodule)
.github/workflows/         Auto-deploy
```

### Run it locally

```bash
git clone --recursive https://github.com/AlexYoung0524/whereistand.github.io.git
cd whereistand.github.io
hugo server -D
```

You'll need the extended edition of [Hugo](https://gohugo.io/). Then open http://localhost:1313.

### Copyright

All posts and images are copyrighted by the author. If you'd like to republish something, send me an email first: jihui.yang0.0@gmail.com
