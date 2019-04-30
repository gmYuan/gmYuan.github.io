---
title: hexo博客搭建

date: 2019-04-21 16:54:58

tags: Hexo

categories: Hexo
---

这周用hexo和github Pages搭建了自己的静态博客，这是过程中的小结记录。
因为主要是用来给自己备忘的，所以只是直接记录了相关的参考文档。
<!-- more -->

## 一 博客搭建过程

1 Q: 如何搭建博客

S1 实现基本博客功能，参考这个文档即可: [hexo教程：github page+独立域名搭建(1)](http://fangzh.top/2018/2018090514/)

S2 配置博客主题，依次参考以下文档:

[01 hexo的next主题个性化配置教程](https://segmentfault.com/a/1190000009544924)

[02 next官方文档](http://theme-next.iissnan.com/getting-started.html)

[03 底部文字居中](https://www.zydarchen.top/20170707/4_hello_blog)

[04 代码块复制功能](https://www.zhyong.cn/posts/ca02/)

S3 利用git分支进行多终端工作，具体可见:

[hexo教程:基本配置+更换主题+多终端工作+coding page部署分流(2)](http://fangzh.top/2018/2018090715/)

S4 发布步骤,代码见下:

```js
hexo clean

hexo s --debug

hexo d

hexo g
```