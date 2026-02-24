# Ink Canvas Sodium (Stable)

基于 icc-0610fix 构建。

> [!IMPORTANT]
> GitHub 上的`icc-0610fix`原始存储库已被删除。永久存档在[这里](https://github.com/LiuYan-xwx/icc-0610fix/tree/e263bc9b357a2bfca300855c86c66b5b9f41f4be)。

以下是原始 ReadMe：（已翻译为简中并注释失效内容）

---

<div align="center">

<img src="icc.png" width="128">

# InkCanvasForClass

Elegant by Default. Based on `ChangSakura/InkCanvas` .

**这将是最后一次基于InkCanvas控件的倔强**

[![UPSTREAM](https://img.shields.io/badge/UpStream-ChangSakura%2FInk--Canvas-red.svg "LICENSE")](https://github.com/ChangSakura/Ink-Canvas)
<!--![Gitea Last Commit](https://img.shields.io/gitea/last-commit/kriastans/InkCanvasForClass?gitea_url=https%3A%2F%2Fgitea.bliemhax.com%2F)-->
[![LICENSE](https://img.shields.io/badge/License-GPL--3.0-red.svg "LICENSE")](https://gitea.bliemhax.com/kriastans/InkCanvasForClass/src/branch/master/LICENSE)
<!--[![交流群](https://img.shields.io/badge/-%E4%BA%A4%E6%B5%81%E7%BE%A4%20825759306-blue?style=flat&logo=TencentQQ)]()
[![Telegram](https://img.shields.io/badge/-Telegram%20@InkCanvasForClass-blue?style=flat&logo=Telegram)](https://t.me/InkCanvasForClass)-->

![Screenshot-1](./Images/icc1.png)
![Screenshot-2](./Images/icc2.png)

</div>

<!--## 赞助支持

我已注册爱发电，感谢各位对icc的支持！[https://afdian.net/a/dubi906w](https://afdian.net/a/dubi906w)

## 新网站即将上线

新网站即将上线，快来一起和InkCanvasForClass见证美好时刻吧！[点我访问](https://icc.bliemhax.com/)-->

## 严正声明

本产品与peppy的osu!以及其周边项目和产品无任何关联，该Logo仅供娱乐用，若有侵权，请联系Dev协商解决。

## 公告

该项目旨在为ICA提供更加舒适和易于使用的UI和用户体验，对于任何墨迹书写方面的Bug如果本人无法修复将不会被修复。

## 前言

使用和分发本软件前，您应当且务必知晓相关开源协议，本软件基于 <https://github.com/ChangSakura/Ink-Canvas> 修改而成，而ICA又基于 <https://github.com/WXRIW/Ink-Canvas> 修改而成，增添了包括但不限于隐藏到侧边栏等功能，更改了相关UI和软件操作逻辑。对于墨迹书写功能以及ICA独有功能的相关 issue 提出，应优先查阅 <https://github.com/WXRIW/Ink-Canvas/issues> 。

<!--[直接下载](https://gitea.bliemhax.com/kriastans/InkCanvasForClass/releases "Latest Releases")
——以压缩包形式存储，便携版可直接启动，默认配置适配绝大多数红外触摸框的设置。-->

> ⚠️注意：此项目仍在开发中，只会在发布正式发行版时提供Release。您可以自行使用VS2022编译打包后自行使用

## 特性

1. Support Active Pen (支持压感)
2. 工具栏显示了每个功能的文字描述
3. 添加了调色盘的颜色
4. 添加了荧光笔支持

## 提示

- 对新功能的有效意见和合理建议，开发者会适时回复并进行开发。本软件并非商业性质软件，请勿催促开发者，耐心才能让功能更少 BUG、更加稳定。
- 此软件仅用于私人使用，请勿商用。更新也不会很快，如果有能力请PR贡献代码而不是在Issue里面提问题。
- 欢迎您使用InkCanvas家族的其他成员，包括ICC和ICA的创始者IC以及和ICC差不多的ICA。您的大力宣传能够帮助我们的软件被更多的用户发现。

## FAQ

### 点击放映后一翻页就闪退？

考虑是由于`Microsoft Office`未启用导致的，请自行启用

### 放映后画板程序不会切换到PPT模式？

如果你曾经安装过`WPS`且在卸载后发现问题则是由于暂时未确定的问题所导致，可以尝试重新安装WPS
> “您好，关于您反馈的情况我们已经反馈技术同学进一步分析哈，辛苦您可以留意后续WPS版本更新哈~” --回复自WPS客服

另外，处在保护（只读）模式的PPT不会被识别

若因安装了最新版本的 WPS 而导致无法在 WPS 软件内进入 PPT 模式，可以尝试卸载 WPS 后，并清除电脑垃圾、注册表垃圾、删除电脑上所有带 "kingsoft" 名称的文件夹，重新安装 WPS 后，（以上步骤可能有多余步骤），经测试在 WPS 内可以正常进入 PPT 模式。

ICC 可以支持 WPS，但目前无法同时支持 MSOffice 和 WPS。若要启用 WPS 支持，请确保 WPS 是否在 “配置工具” 中开启了 “WPS Office 相容第三方系统和软件” 选项，该项目勾选并应用后，将无法检测到 MS Office 的COM接口。

如果您安装了“赣教通”、“畅言智慧课堂”等应用程序，可能会安装“畅言备课精灵”，可能会导致遗失64为Office COM组建的注册且目前似乎无法修复（可以切换到新用户正常使用）。但 WPS Office 可以正常使用。

若要将 ICC 配合 WPS 使用，可打开“WPS 演示”后，前往“文件” - “选项” ，取消勾选“单屏幕幻灯片放映时，显示放映工具栏”该项，获得更好的体验。若要将 ICC 配合 MS Office 使用，可以打开 Powerpoint，前往“选项” ，“高级”，取消勾选“显示快捷工具栏”，获得更好的体验。

### **安装后**程序无法正常启动？

请检查你的电脑上是否安装了 `.Net Framework 4.7.2` 或更高版本。若没有，请前往官网下载

> 遇到各种奇葩逗比问题请重启应用程序，如果不行请反馈给Dev解决！

<!--## 如何联系我

1. QQ群聊：825759306
2. Telegram频道：@InkCanvasForClass-->

## 特别鸣谢

<table>
    <tbody>
        <tr>
            <td align="center" valign="top" width="14.28%"><a href="https://github.com/ChangSakura"><img
                        src="https://avatars.githubusercontent.com/u/90511645?v=4" width="100px;"
                        alt="HelloWRC" /><br /><sub><b>ChangSakura</b></sub></a></td>
            <td align="center" valign="top" width="14.28%"><a href="https://github.com/WXRIW"><img
                        src="https://avatars.githubusercontent.com/u/62491584?v=4" width="100px;"
                        alt="Doctor-yoi" /><br /><sub><b>WXRIW</b></sub></a></td>
            <td align="center" valign="top" width="14.28%"><a href="https://github.com/Alan-CRL"><img
                        src="https://avatars.githubusercontent.com/u/92425617?v=4" width="100px;"
                        alt="姜胤" /><br /><sub><b>Alan-CRL</b></sub></a></td>
        </tr>
    </tbody>
</table>
