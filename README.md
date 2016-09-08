# [Solo](https://github.com/b3log/solo) [![Build Status](https://img.shields.io/travis/b3log/solo.svg?style=flat)](https://travis-ci.org/b3log/solo) [![Coverage Status](https://img.shields.io/coveralls/b3log/solo.svg?style=flat)](https://coveralls.io/github/b3log/solo?branch=master)  [![Apache License](http://img.shields.io/badge/license-apache2-orange.svg?style=flat)](http://www.apache.org/licenses/LICENSE-2.0) [![Download](http://img.shields.io/badge/download-~6.2K-blue.svg?style=flat)](http://pan.baidu.com/share/link?shareid=541735&uk=3255126224)

![Solo](http://img.blog.csdn.net/20160909004212828)

## 简介

[Solo](https://github.com/b3log/solo) 是一款**一个命令**就能搭建好的 Java 开源博客系统，并内置了 15+ 套精心制作的皮肤。除此之外，Solo 还有着非常活跃的[社区](https://hacpai.com/b3log)，文章分享到社区后可以让很多人看到，产生丰富的交流互动。

## 功能 

Solo 沉淀至今的**每一个功能你应该都会用到**。我们不会将只有“20%”用户使用的功能添加进来，只有这样才能保持博客系统本该有的纯净，足够轻量才能带来简约的使用体验。

* Markdown / TinyMCE / KindEditor
* 自定义导航（页面、链接）
* 草稿夹
* 评论/回复邮件提醒
* 随机文章 / 相关文章 / 置顶 / 更新提醒
* 自定义文章永久链接
* 自定义站点 SEO 参数
* 自定义公告 / 页脚
* 多个签名档
* 代码高亮
* 多皮肤，多端适配
* 多语言 / 国际化
* 上传七牛云
* 友情链接管理
* 多用户写作，团队博客
* SQL 文件导出
* 插件系统
* Atom / RSS 订阅
* Sitemap
* MetaWeblog API

如果有新版可用，升级过程也是非常简单的，只需要重新部署新版本就可以，不用运行额外的任何脚本。

另外，如果你想让我们将 Solo 修改为 CMS，我们只能对你说：“出门[右转](https://github.com/WordPress/WordPress)”。 

## 安装

JDK 环境准备好之后[下载](http://pan.baidu.com/share/link?shareid=541735&uk=3255126224)最新的 Solo 包解压，进入解压目录执行：

* Windows: `java -cp WEB-INF/lib/*;WEB-INF/classes org.b3log.solo.Starter`
* Unix-like: `java -cp WEB-INF/lib/*:WEB-INF/classes org.b3log.solo.Starter`

执行完成后顺利的话你就可以看到 Solo 的初始化界面了 :tada: 

详细的配置请浏览[用户指南](https://github.com/b3log/solo/wiki/standalone_mode)。如果你碰到问题，请提 [issue](https://github.com/b3log/solo/issues/new) 或到[社区](https://hacpai.com/tag/Solo)发帖，我们会尽量在第一时间帮助你解决问题。

另外，如果你想用 Solo 但又不想自己维护服务器，那可以尝试购买我们搭建好的 Solo 直接[使用](http://b3log.org/services/#solo)。

## 技术

为了尽量降低服务器的内存占用，顺带尝试[一些技术构想](https://hacpai.com/article/1403847528022)，我们开发了  [Latke](https://github.com/b3log/latke) 框架，并在此基础上构建了 Solo、Sym、XiaoV 等产品。这些产品反过来也会对框架提出需求，这是一个相互促进，共同演化的良性发展过程。

Solo 的前端部分为了降低复杂度， 只依赖于 jQuery、编辑器、代码高亮等组件。管理后台的 SPA 框架、皮肤响应式 UI 都是我们自己实现的。

**没有最好的轮子，只有最适合的轮子。** BTW，如果你想研究如何制造 Web 轮子，Solo 是一个不错的入口。

## 文档

* [用户指南](https://github.com/b3log/solo/wiki/standalone_mode)：安装、配置、常见问题
* [开发指南](https://github.com/b3log/solo/wiki/Pre_dev)：开发环境、项目结构、框架说明
* [皮肤开发](https://github.com/b3log/solo/wiki/Develop_steps)：开发步骤、模版变量
* [插件开发](https://docs.google.com/document/pub?id=15H7Q3EBo-44v61Xp_epiYY7vK_gPJLkQaT7T1gkE64w&pli=1)：插件机制、处理流程

## 版本历史

Solo 的**第一个版本发布于 2010 年**，我们对每个版本都进行了详细的变更记录，[这里](http://solo.b3log.org/CHANGE_LOGS.html)可以看到 Solo 成长的全貌 :seedling:

每一次开发新版本时我们都会在开发分支上进行，尽量避免给其他开发者们带来困扰。因为我们知道只有专业和尽责才能让 Solo 这个开源项目走得更远，**谁让你我的征途是星辰和大海呢！**

## 贡献

Solo 的主要作者是 [Daniel](https://github.com/88250) 与 [Vanessa](https://github.com/Vanessa219)，所有贡献者可以在[这里](https://github.com/b3log/solo/graphs/contributors)看到。

我们非常期待你加入到这个项目中，无论是使用反馈还是代码补丁，都是对 Solo 的一份满满的爱 :heart:

## Terms

* This software is open sourced under the Apache License 2.0
* You can not get rid of the "Powered by [B3log 开源](http://b3log.org)" from any page, even which you made
* If you want to use this software for commercial purpose, please mail to support@liuyun.io for a commercial license request
* Copyright &copy; b3log.org, all rights reserved

## 鸣谢

Solo 的诞生离不开以下开源项目：

* [jQuery](https://github.com/jquery/jquery)：使用最广泛的 JavaScript 工具库
* [CodeMirror](https://github.com/codemirror/CodeMirror)：Markdown 编辑器内核
* [KindEditor](https://github.com/kindsoft/kindeditor)：一个富文本编辑器
* [TinyMCE](https://github.com/tinymce/tinymce)：又一个富文本编辑器
* [SyntaxHighlighter](https://github.com/syntaxhighlighter/syntaxhighlighter)：一个代码高亮库
* [Highlight.js](https://github.com/isagalaev/highlight.js)：又一个代码高亮库
* [emojify.js](https://github.com/Ranks/emojify.js)：前端 Emoji 处理库
* [jsoup](https://github.com/jhy/jsoup)：Java HTML 解析器
* [pegdown](https://github.com/sirthias/pegdown)：Java Markdown 处理库
* [Apache Commons](http://commons.apache.org)：Java 工具库集
* [emoji-java](https://github.com/vdurmont/emoji-java)：Java Emoji 处理库
* [H2](https://github.com/h2database/h2database)：Java SQL 数据库
* [Jetty](https://github.com/eclipse/jetty.project)：轻量级的 Java Web 容器
* [Latke](https://github.com/b3log/latke)：简洁高效的 Java Web 框架 
* [NetBeans](https://netbeans.org)：全宇宙暂时排名第三的 IDE

----

Logo 征集中....

----

## 界面截图 

## 后台

* Admin - Post (TinyMCE/Markdown)
![Admin - Post (TinyMCE/Markdown)](http://img.blog.csdn.net/20160909003905083)
* Admin - Skins 
![Admin - Skins ](http://img.blog.csdn.net/20160909003855114)

## 内置的皮肤

* [next](https://github.com/b3log/solo-skins/tree/master/next)
![next](http://img.blog.csdn.net/20160908232930827)

* [yilia](https://github.com/b3log/solo-skins/tree/master/yilia)
![yilia](http://img.blog.csdn.net/20160908232913225)

* [finding](https://github.com/b3log/solo-skins/tree/master/finding)
![finding](http://img.blog.csdn.net/20160908232943335)

* [metro-hot](https://github.com/b3log/solo-skins/tree/master/metro-hot)
![metro-hot](http://img.blog.csdn.net/20160908233003148)

* [timeline](https://github.com/b3log/solo-skins/tree/master/timeline)
![timeline](http://img.blog.csdn.net/20160908233015843)

* [ease](https://github.com/b3log/solo-skins/tree/master/ease)
![ease](http://img.blog.csdn.net/20160908233024047)

* [mobile](https://github.com/b3log/solo-skins/tree/master/mobile)

![mobile](http://img.blog.csdn.net/20160908233032196)

* [andrea](https://github.com/b3log/solo-skins/tree/master/andrea)
![andrea](http://img.blog.csdn.net/20160909004722157)

* [classic](https://github.com/b3log/solo-skins/tree/master/classic)
![classic](http://img.blog.csdn.net/20160908233049265)

* [community](https://github.com/b3log/solo-skins/tree/master/community)
![community](http://img.blog.csdn.net/20160908233057493)

* [favourite](https://github.com/b3log/solo-skins/tree/master/favourite)
![favourite](http://img.blog.csdn.net/20160908233110391)

* [tree-house](https://github.com/b3log/solo-skins/tree/master/tree-house)
![tree-house](http://img.blog.csdn.net/20160908233120891)

* [i-nove](https://github.com/b3log/solo-skins/tree/master/i-nove)
![i-nove](http://img.blog.csdn.net/20160908233131516)

* [neoease](https://github.com/b3log/solo-skins/tree/master/neoease)
![neoease](http://img.blog.csdn.net/20160908233139713)

* [owmx-3.0](https://github.com/b3log/solo-skins/tree/master/owmx-3.0)
![owmx-3.0](http://img.blog.csdn.net/20160908233148135)

* [bruce](https://github.com/b3log/solo-skins/tree/master/bruce)
![bruce](http://img.blog.csdn.net/20160908233157432)

## 社区贡献的皮肤

* [bootstyle](https://github.com/b3log/solo-third-skins/tree/master/bootstyle)
![bootstyle](http://img.blog.csdn.net/20160909002324766)

* [Dot-B](https://github.com/b3log/solo-third-skins/tree/master/Dot-B)
![Dot-B](http://img.blog.csdn.net/20160909002509003)

* [Shawn](https://github.com/b3log/solo-third-skins/tree/master/Shawn)
![Shawn](http://img.blog.csdn.net/20160909002540133)

* [Coda](https://github.com/b3log/solo-third-skins/tree/master/Coda)
![Coda](http://img.blog.csdn.net/20160909002603399)

* [5styles](https://github.com/b3log/solo-third-skins/tree/master/5styles)
![5styles](http://img.blog.csdn.net/20160909002641837)

* [idream](https://github.com/b3log/solo-third-skins/tree/master/idream)
![idream](http://img.blog.csdn.net/20160909002659993)
