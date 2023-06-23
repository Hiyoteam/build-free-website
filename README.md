# build-free-website
![](https://img.shields.io/badge/%E6%96%B0%E6%89%8B%E5%90%91%E9%83%A8%E7%BD%B2%E5%85%8D%E8%B4%B9%E7%BD%91%E7%AB%99%E7%9A%84%E6%95%99%E7%A8%8B%E3%80%82-A%20tutorial%20for%20newbies%20towards%20deploying%20free%20websites-gray.svg)  
  

![](https://img.shields.io/badge/Version-0.01-white.svg)![](https://img.shields.io/badge/Made%20by-Hiyoteam-green.svg)[![](https://shields.io/badge/Community-discord-green?logo=discord&style=social)](https://discord.gg/UzdZCBXvsH)

本教程致力于教您**免费**创建自己的个人网站。
# 方法1：Github Pages

如果你想要一个简单易用的建站方式，那么Github Pages和Markdown组合就是一个不错的选择。下面将介绍如何使用这种方式建立自己的网站。

首先，你需要一个Github账号和一个代码仓库。在仓库中，创建一个新的分支，名称为“gh-pages”。这个分支会被用来托管你的网站。

接下来，你需要选择一个合适的主题。可以在Github上搜索“Jekyll themes”，然后找到一个适合自己的主题，并将其fork到自己的仓库中。然后，在主题中创建一个Markdown文件，这个文件会自动转换为HTML页面，成为你的网站的一部分。

在Markdown文件中，你可以使用Markdown语法来编写内容，例如标题、段落、列表、链接等等。同时，还可以使用一些特殊的标记来添加代码块、图片和表格等其他元素。

一旦你完成了Markdown文件的编写，将它们推送到“gh-pages”分支，Github Pages就会自动构建和发布你的网站。你可以在网址`https://你的用户名.github.io/你的仓库/`中查看它。

现在，让我们来看一下这种建站方式的优缺点。

### 好处：

 - 简单易用：使用Markdown编写网站内容非常容易学习，而且Github Pages提供了自动构建和托管功能，省去了很多麻烦。
 - 免费：Github Pages是免费的，不需要支付任何费用。
 - 版本控制：Github Pages和Git代码仓库集成，可以方便地管理版本和修改历史记录。
### 缺点：

 - 有限制：Github Pages虽然功能强大，但也有一些限制，例如每个仓库最多只能有一个网站，每个月有带宽和存储限制等。
 - 依赖Github：这种方式依赖于Github的稳定性和可用性，如果Github出现问题，你的网站也可能受到影响。
 - 总的来说，如果你想要一个简单、免费且易于维护的网站，那么使用Github Pages和Markdown是一个不错的选择。它不仅适合个人博客和简单的网站，也可以用于小型商业网站和在线文档。
# 方法2：Replit

如果你想运行一些程序（如PHP,ASP,Flask）在网站服务器，Replit是一个不错的选择。

首先，您需要注册一个Replit账号，在主页进行Craft操作,从搜索框中找到您网站程序的语言，创建一个repl。

接着，进入这个repl，点击run即可启动网站，右侧的视图将会弹出弹窗，为您网站的浏览，上方的地址栏为您网站的网址。

### 绑定域名:

首先您需要打开浏览试图，点击铅笔形状的按钮，输入您要绑定的域名。
接着，在您域名的DNS，你需要根据提示添加一个TXT记录和一个CNAME记录（如果用的是跟域名，Replit显示你项目的A记录）。
点击完成后即可绑定域名，有时可能需要等待一段时间
### 好处：

 - 可以支持动态程序
 - 免费：Replit的基础版完全免费！
 - 版本控制：Replit和Git代码仓库集成，可以方便地管理版本和修改历史记录。
 - 内置Nix包管理器：这解决了Replit没有Root权限的问题，你可以通过Nix来代替部分需要Root安装的软件包。

### 缺点：
 - 空间和配置有限：Replit虽然非常的强大，但有一些空间和配置的限制，因此，Replit只适合内存、空间、性能需求小的程序，较大的程序是带不动的。
 - 休眠机制：Replit无法长期运行程序，如果长期无人访问网页就会自动休眠，这种情况需要运行监视器（例如：UptimeRobot、BetterUptime）来解决。
 - 无法创建私有项目：如果在Replit搭建网页时使用公开项目，网页会有一定的危险，攻击者可以在Replit上查看配置文件或下载数据库来获取后台密码，除非项目必须在命令行操作或将密码存储在Secrets，这个问题可以通过申请Education Team，并将项目存放在其中解决。
 - 无Root权限：Replit是没有Root权限的，这会导致一些依赖Root权限的程序无法运行。
