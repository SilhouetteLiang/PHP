---
title: 1hexo操作
date: 2020-09-17 17:42:37
tags: 技术
---


Quick Start
Create a new post
        `$ hexo new "My New Post"`

Run server
        `$ hexo server`

Generate static files
        `$ hexo generate`
        `$ hexo deploy`

这是
一个
新的


HEXO

第一种解释：
        https://www.jianshu.com/p/f56a876a9bd1

        cd /var/www/markdown/blog
        blog下执行     sudo hexo s

第二种解释：

https://www.jianshu.com/p/13e64c9e2295

不错的。




3.发布文章
终端cd到blog文件夹下，执行如下命令新建文章：

hexo new "postName" 

名为postName.md的文件会建在目录/blog/source/_posts下。你当然可以用vim来编辑文章。我在用Mou编辑器，支持预览，虽然其预览主题并非我喜欢，如果你有好用的markdown编辑器请推荐给我，感激不尽！
文章编辑完成后，终端cd到blog文件夹下，执行如下命令来发布：

第一种：
hexo generate                 //生成静态页面
hexo deploy                   //将文章部署到Github
至此，Mac上搭建基于Github的Hexo博客就完成了。下面的内容是介绍安装theme，添加评论功能和绑定个人域名，如果有兴趣且还有耐心的话，请继续吧。

第二种：

Git   add 
Git   ci 
Git   push 
