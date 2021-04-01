# 「 **VLOOK™ ── 让你的 Markdown 有了新看(wán)法** 」

**开源中国（[OSChina.net](https://www.oschina.net/p/vlook)）推荐的国产开源产品。**

![VLOOK™](https://cdn.jsdelivr.net/gh/MadMaxChow/VLOOKres@master/pic/vlook-mark-light.svg)

[VLOOK™](https://github.com/MadMaxChow/VLOOK) 是针对 [Typora](https://www.typora.io)（跨平台 Markdown 编辑器）的 **主题包** 和 **增强插件**（针对导出的 HTML 文件）。

[VLOOK™](https://github.com/MadMaxChow/VLOOK) is a **Theme Pack** and **Enhanced Plug-in** for [Typora](https://www.typora.io) (for exported HTML files).

VLOOK™ 也许是目前最好的 Markdown 增强插件之一，也是**开源中国（[OSChina.net](https://www.oschina.net/p/vlook)）推荐的国产开源产品。**

VLOOK™ 属于开源软件，遵从 **[MIT 许可证](#许可协议)**。

> **[加入 VLOOK™ 官方Q群：805502564](https://qm.qq.com/cgi-bin/qm/qr?k=oB8wpFG_4SEMf1CL9qVy-jMw0CMfSwff&jump_from=webapi&)**

---

![让 Markdown 的自动化排版和交互性上了 N 个台阶](https://z3.ax1x.com/2021/03/30/cF20BD.png)

![内置多套原创文档主题、字体主题，一键切换，支持私人定制](https://z3.ax1x.com/2021/03/30/cF2wnO.png)

![表格排版+：单元格合并、列格式、表格行分组、自动编号、…](https://z3.ax1x.com/2021/03/30/cF2ajK.png)

![零成本的图片自动排版～题注、高分屏、反色、替换、版式、…](https://z3.ax1x.com/2021/03/30/cF2rAH.png)

![火力全开的图片自动排版、演示辅助～聚光灯、激光笔、注意](https://z3.ax1x.com/2021/03/30/cF2t91.png)

![OMG! 可以按大纲、逐章、段落、插图多种方式导航](https://z3.ax1x.com/2021/03/30/cF2N1x.png)

![完美适配 Dark 模式，Markdown 变得更 Cool 了](https://z3.ax1x.com/2021/03/30/cF2BHe.png)

![音/视频、标签、引用折叠、高清插图、…30+特性开箱即用](https://z3.ax1x.com/2021/03/30/cF2Uc6.png)

---

# 打赏

**若喜欢 VLOOK™ 的话，可以贡献一杯咖啡 :-)**<br />
![打赏 VLOOK™](https://z3.ax1x.com/2021/01/24/sHf82D.png)

---

# 如何使用

## Step 1•下载与配置

1. **下载插件：**
   1. 从 VLOOK™ 在 ![Github](https://s1.ax1x.com/2020/11/11/BjMANq.png?mode=icon&darksrc=invert)**[GitHub](https://github.com/MadMaxChow/VLOOK/releases)** 或 ![Gitee](https://s1.ax1x.com/2020/11/06/BWBGmq.png?mode=icon)**[Gitee](https://gitee.com/madmaxchow/VLOOK/releases)** 的主页下载最新发布的版本
2. **安装字体：（可选）**
   1. 下载并安装 VLOOK™ 主题配套字体包 •• 详见「[字体主题](#字体主题)」
3. **安装 Typora：**
   1. 下载并安装 ![Typora](https://s3.ax1x.com/2020/11/13/DpZXtI.png?mode=icon)[Typora](https://www.typora.io) 的最新版本
   2. 启动后进入「偏好设置」，并开启以下选项。详见下图：

![开启「偏好设置 ▸ Markdown」下的相关的选项」下的所有选项](https://z3.ax1x.com/2021/01/24/sHR4wq.png)


## Step 2•安装并选择主题

1. **安装主题：**
   1. 将`released\theme`下所有 CSS 文件复制至 Typora 的主题目录（ Typora「偏好设置」中点击「外观 - 打开主题目录」定位到该目录）；
2. **选用主题：**
   1. 重启 Typora
   2. 点击菜单`主题`，选择以`vlook-*`形式命名的主题即可
3. **编写文档：**
   1. 建议基于 VLOOK™ 提供的文档模板来创建，这样能更快上手
   2. 模板文件位于`released`下的`VLOOK-Document-Template.md` 为模板来创建你自己的 Markdown 文档

## Step 3•应用插件

首先在 Typora 中将 Markdown 文件导出为「**HTML**」文件；

###### 方式一（仅适用于 Windows 用户）：

1. 启动自动植入插件小工具：released\\plugin\\**v-drop.exe**
2. 启动 v-drop.exe，并将导出后的「HTML」文件拖到其界面上即可
3. 说明：默认自动读取 `plugin.txt` 的内容，该文件的默认内容为离线版插件，根据需要选择在线版内容进行覆盖。

###### 方式二：

1. 根据需要打开对应的「插件文件」，全选所有内容，并复制
   - 在线版插件（自动在线更新）：released\\plugin\\**plugin_live.txt**
   - 离线版插件（无网络场景）：released\\plugin\\**plugin_standalone.txt**

2. 用纯文件编辑器，如：记事本、[Visual Studio Code](https://code.visualstudio.com/)，打开导出后的 HTML 文件；
3. 搜索`<body`，并将复制的内容粘贴到 body 标签所在行的关闭符`>`之后：

```html
<body ...>
◀ ◀ ◀ 将「插件内容」粘贴于此！
...
</body>
```

1. 保存，大吉大利。

###### 选择合适的浏览器

> 强烈建议使用以下浏览器进行访问：
>
> Google **[Chrome](https://www.google.cn/chrome/)**　　Microsoft **[Edge](https://www.microsoft.com/zh-cn/edge)**(Chromium)　　Mozilla **[Firefox](https://www.mozilla.org/zh-CN/firefox/)**

---

# 字体主题

「**模板主题让文档颜值倍增，而字体则是文档气质担当！**」

VLOOK™ 提供了两套字体风格，可根据个人喜好进行选用。

> **小•清•新**
>
> 整体视觉为「**清新、简约、明快**」，主要采用无衬线的免费或开源的东亚和拉丁字体。
>
> ![字体风格_小清新](https://s3.ax1x.com/2021/01/05/skBoA1.png)

> **文•艺•范**
>
> 整体视觉为「**优雅、韵动、个性**」，主要采用衬线、无衬线的免费或开源的东亚和拉丁字体，多种字重进行**混搭组合**。
>
> ![字体风格_文艺范](https://s3.ax1x.com/2021/01/05/skBLcD.png?darksrc=invert&srcset=skBjnH.png@2x,skBOje.png@3x)

**因为 Windows / MacOS 系统默认不预装字体主题配套的字体包，VLOOK™ 目前可同时支持在线和本地两种使用方式。**
**若你的工作环境无法访问互联网，建议直接下载字体包并安装到本地，以获得最佳的视觉体验。**

![蓝奏云](https://s3.ax1x.com/2020/12/13/reJiee.png?mode=logo&srcset=reJCLD.png@2x) ••• [下载字体▾](https://wws.lanzous.com/ieVDhj1aokj)

![百度网盘](https://s3.ax1x.com/2020/12/13/reJFdH.png?mode=logo&srcset=reJkod.png@2x) •••`密码：11ta`••• [下载字体▾](https://pan.baidu.com/s/1gH5Hj-X3-LCaOLtN0AxLLw)

---

# 快速参考手册

VLOOK™ 通过持续**挖掘和扩展** Markdown 和 CSS，并结合文档的互联网化应用场景，在 **文档排版**、**内容导航**、**演示辅助**、**交互体验** 等方面提供了 **一致**、**简洁**、**友好** 的体验。

> - 有关 VLOOK™ 特性的详细介绍、样例及使用说明详见《VLOOK™ 快速参考手册》••• [GitHub](https://madmaxchow.github.io/VLOOK/index.html) • [Gitee](https://madmaxchow.gitee.io/vlook/index.html)

> - 有关脚本化图表的详细介绍、样例及使用说明详见《脚本化图表参考指南》••• [GitHub](https://madmaxchow.github.io/VLOOK/chart.html) • [Gitee](https://madmaxchow.gitee.io/vlook/chart.html)

---

# 私人定制主题

目前 VLOOK™ 项目已开放了主题的 **私人定制** 服务，定制样品示例如下：

![私人定制主题](https://s3.ax1x.com/2021/01/27/szoo9S.png)

（以上仅为效果仅为样品展示，非正式定制服务成品）

私人定制主题服务微信：**MaxChow**

---

# 目录说明

| 目录 | 说明                         |
| ---------- | ---------------------------- |
| [ **docs** ] | VLOOK™ 快速参考手册、官网及在线服务相关文件 |
| [ **released** ] | 发布版本的主目录          |
| ├&nbsp;&nbsp;┠─ [ **demo** ] | 基于 VLOOK™ 主题的 Markdown 示例文件 |
| ├&nbsp;&nbsp;┠─ [ **theme** ] | 主题文件                     |
| ├&nbsp;&nbsp;┖─ [ **plugin** ] | 插件主目录                |
| ├&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;┠─ plugin.txt | 自动植入版本_插件（通过 `v-drop.exe` 自动植入，内容可从以下两个版本中复制进行覆盖） |
| ├&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;┠─ plugin_live.txt | 在线版本°插件 |
| ├&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;┖─ plugin_standalone.txt | 离线版本°插件 |
| [ **src** ] | 源码目录                     |
| ├&nbsp;&nbsp;┠─ [ **dev** ] | 开发测试用文件 |
| ├&nbsp;&nbsp;┠─ [ **less** ] | 主题 CSS 文件的源文件 |
| ├&nbsp;&nbsp;┖─ [ **logo** ] | VLOOK™ 的 logo 资源 |