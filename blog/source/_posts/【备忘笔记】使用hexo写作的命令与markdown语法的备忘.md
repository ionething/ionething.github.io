---
title: 【备忘笔记】使用hexo写作的命令与markdown语法的备忘
date: 2018-04-08 22:11:34
categories: 工具
tags:
- hexo
- markdown
---
> 很久没有写过博客了，把仓库clone下来之后都遗忘了如何操作。找到文档仔细研读之后，才依稀记起一些命令。现决定先记录下来，等以后忘记的时候只需本文查阅即可。

# Hexo常用

### 写作

1. 创建一篇新的文章
    ```
    hexo new <title>
    ```
1. Front-matter是文件上方```---```分割的区域，可以指定以下变量
    - layout：布局，可以为false，这样文章就不会被处理

### 生成与部署

1. 生成文件
    ```
    hexo g
    ```

1. 部署
    ```
    hexo d
    ```

1. 完成后部署
    ```
    hexo g -d
    ```
    或者
    ```
    hexo d -g
    ```

# Markdown语法
<pre>
# 标题
** 加粗
``` ``` 代码
[百度1](http://www.baidu.com/"百度一下"){:target="_blank"} 超链接
> 引用
</pre>

# 参考文档
- [Hexo中文文档](https://hexo.io/zh-cn/docs/)
- [Next中文文档](http://theme-next.iissnan.com/getting-started.html)
- [阮一峰老师的写作规范](https://github.com/ruanyf/document-style-guide)
- [Markdown: Basics](http://wowubuntu.com/markdown/basic.html)
- [Markdown语法说明](http://wowubuntu.com/markdown/index.html)
- [Markdown常用笔记语法](https://ouweiya.gitbooks.io/markdown/)