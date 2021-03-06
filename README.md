<p align="center">
<img src="https://pc.woozooo.com/img/logo2.gif" width="200">
</p>

<h3 align="center">- 蓝奏云CMD -</h3>

<p align="center">
<img src="https://img.shields.io/github/v/release/zaxtyson/LanZouCloud-CMD.svg?logo=iCloud">
<img src="https://img.shields.io/badge/support-Windows-blue?logo=Windows">
<img src="https://img.shields.io/badge/support-Linux-yellow?logo=Linux">
</p>

# 界面

![](https://www.6000tu.com/images/2020/01/17/image.png)

# 说明
- 为了方便管理，API独立为一个项目[LanZouCloud-API](https://github.com/zaxtyson/LanZouCloud-API)
- 在 Linux 平台使用时，您需要安装 `rar` 工具，然后在 `config.ini`中设置它的路径
- 默认下载路径为 `D:\LanZouCloud`，请使用 `setpath` 命令修改
- 可以使用 `down 分享链接` 的方式下载文件(夹)~
- 关注本页面以获取更新，如果有问题或者建议，请提 issue
- 如果喜欢本项目，请给一个 star (^▽^)/
- 使用说明请移步 [Wiki](https://github.com/zaxtyson/LanZouCloud-CMD/wiki) 页面

# 下载

- 在蓝奏云网盘下载 [Windows版](https://www.lanzous.com/b0f14h1od) 

- 或者在本项目的 [`releases`](https://github.com/zaxtyson/LanZouCloud-CMD/releases) 板块下载

# GUI 版

感谢 [rachpt](https://github.com/rachpt/lanzou-gui) 开发的 GUI 版本，[点我](https://github.com/rachpt/lanzou-gui/wiki)查看详情

# `v2.3.1` 更新说明
- 界面焕然一新
- 修复了一堆 BUG
- 新增设置描述信息功能
- 完善了回收站功能
- 完善了移动文件功能

# `v2.2.1` 更新说明
- 修复了文件(夹)无法下载的问题 [#4](https://github.com/zaxtyson/LanZouCloud-CMD/issues/4)
- 修复了上传 rar 分卷文件被 ban 的问题
- 修复了无后缀文件上传出错的问题
- 修复了文件中空白字符导致上传和解压失败的问题

# `v2.1` 更新说明
- 修复了蓝奏云分享链接格式变化导致无法获取直链的问题

# `v2.0`更新说明
- 修复了登录 `formhash` 的错误
- 增加了上传/下载的进度条 [#1](https://github.com/zaxtyson/LanZouCloud-CMD/issues/1)
- 使用 RAR 分卷压缩代替文件分段 [#2](https://github.com/zaxtyson/LanZouCloud-CMD/issues/2)
- 修复了连续上传大文件被ban的问题 [#3](https://github.com/zaxtyson/LanZouCloud-CMD/issues/3)
- 增加了回收站功能
- 取消了`种子文件`下载方式，自动识别分卷数据并解压
- 增加了通过分享链接下载的功能
