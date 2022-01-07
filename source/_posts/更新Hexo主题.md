---
title: 更新Hexo主题
categories:
  - 网站搭建笔记
tags:
  - Hexo
id: update-Hexo-theme 
---

## 引子

<div class="info">

> 本文章适用于不小心更改了主题的<code>_config.yml</code>的人

</div>

不知不觉间，博客已经搭建结束两三个月了。主题使用的是[Yun](https://github.com/YunYouJun/hexo-theme-yun)主题，更新到了[1.7.0版本](https://github.com/YunYouJun/hexo-theme-yun/releases/tag/v1.7.0)，其中“添加 Waline Dark Mode 的默认配置”是我最喜欢的功能了 ~~再不更新小窝就要结蜘蛛网了🕊~~

## 正文

本来说更新主题是挺简单的吧 ~~什么？你用动态博客？当我没说~~

但作者在[说明文档](https://yun.yunyoujun.cn/guide/config.html)里提到：

<div class="danger">

> 请在 `source/_data/yun.yml` 中定义您所需要的配置，其余将自动使用主题的默认配置。
>
> 如未特殊说明，皆默认在 `yun.yml` 文件中配置。
>
> 请最好不要对主题的任何文件进行修改，除非你确认你拥有一定的开发能力或此后将不会对主题进行升级。

</div>

（无语.jpg）

不得不说我自己是真的手贱，在开发的时候把主题的`_config.yml`改的面目全非 ~~升级`Hexo`的时候是不是得崩溃~~

但是——

方法总比困难多 ~~你就搁着找理由去吧~~

### 正正文

我把改的面目全非的`_config.yml`复制到了桌面上

然后按照一般的主题更新流程，把原来的主题给覆盖了

然后

```bash
hexo s
```

然后按照桌面的`_config.yml`配置 `source/_data/yun.yml` 
