---
layout: default
title: 常见问题
description: Frequently Asked Questions
---

# 网络

网络问题一般表现为弹出对话框 "An error occurred while sending the request..." 遇见网络问题可采用以下方法尝试解决.

0. 请检查设备网络的连接情况, 以及是否可以正常访问网易服务器;
1. 如果您使用的是 WLAN 网络, 请前往 " 设置⚙️ - 网络和Internet - WLAN - 选择能够使用你的WLAN数据的应用 - 启用 LyricEase 的 WLAN 权限".
2. 某些版本存在网络代理下无法使用的问题. 请使用 Powershell 运行以下指令: `CheckNetIsolation.exe loopbackexempt -a -p=S-1-15-2-3740683252-4218607605-2448778852-3644121063-1212457277-1263217692-2375173846` . 我们后续将支持使用自定义网络代理。
3. 部分用户反馈在设置 DNS 后无法使用, 可尝试将 DNS 设置为 "自动获取" 解决.
4. 歌曲播放过程中出现断网现象引起的音频加载失败, 在 v0.9.94 版本中我们尚未解决, 我们将在 v0.10 或以前版本中修复.
5. 若仍存在问题请[联系我们](https://github.com/brandonw3612/LyricEase/issues).

...