# MHY_Scanner

<p align="center">
  <img src="docs/assets/readme-banner.svg" alt="Repository overview banner" width="100%" />
</p>

<p align="center">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows" />
  <img alt="Version" src="https://img.shields.io/badge/Version-v1.1.15-DB2777?style=flat-square" />
  <img alt="Login" src="https://img.shields.io/badge/Login-QR_capture-4F46E5?style=flat-square" />
  <img alt="Accounts" src="https://img.shields.io/badge/Accounts-Multi--account-16A34A?style=flat-square" />
</p>

<p align="center"><a href="#功能和特性">功能</a> · <a href="#目前可用的平台">支持游戏</a> · <a href="#使用说明">使用说明</a> · <a href="#编译">编译</a></p>

## 一眼看懂

| 维度 | 说明 |
| --- | --- |
| 用途 | 从屏幕或直播流识别二维码，辅助米哈游游戏账号登录 |
| 账号管理 | 表格化管理多个账号，并支持自定义备注 |
| 当前游戏 | 崩坏 3、原神、崩坏：星穹铁道、绝区零（具体渠道以下表为准） |
| 直播来源 | 现有说明列出 B 站与抖音直播间 RID |
| 分发提示 | 下方 Star 与 Releases 地址仍指向 `Theresa-0328/MHY_Scanner` 上游仓库 |

> 下载构建产物前，请先确认你要使用的是本仓库版本还是上游 Release，避免代码与二进制版本不一致。

---


<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/Theresa-0328/MHY_Scanner?color=blue&style=for-the-badge)](https://github.com/Theresa-0328/MHY_Scanner/stargazers)
</div>

### **版本 - v1.1.15**

## 说明
本项目为免费开源项目，用于学习和研究，禁止商业化用途。

## 功能和特性
- 从屏幕自动获取二维码登录，适用于大部分登录情景，不适用于在竞争激烈时抢码。
- 从直播流获取二维码登录，适用于抢码登录情景。
- 可选启动后自动开始识别屏幕和识别完成后自动退出，无需登录后手动切窗口关闭。
- 表格化管理多账号，方便切换游戏账号。
 
## 目前可用的平台
|   崩坏3    | 原神  | 星穹铁道 | 绝区零 |
| :--------: | :---: | :------:| :----: |
|    官服    | 官服  |   官服   |  官服  |
| BiliBili |       |         |        |

## 使用说明
[点击Releases](https://github.com/Theresa-0328/MHY_Scanner/releases) 选择最新版本下载解压

[点击下载安装Visual C++ 运行时库](https://aka.ms/vs/17/release/vc_redist.x64.exe)，详细解释查看[Microsoft官方文档](https://learn.microsoft.com/zh-cn/cpp/windows/latest-supported-vc-redist?view=msvc-170)。

运行 MHY_Scanner.exe

点击菜单栏 **账号管理->添加账号**，添加你的账号。

双击账号对应的备注单元格可以添加自定义备注。

登陆后点击 **监视屏幕** 就可以自动识别任意显示在屏幕上的二维码并自动登录。

选择你需要的直播平台,在当前直播间输入框输入`RID`，点击 **监视直播间** 就可以自动识别该直播间显示的二维码并自动登录。

正在执行的任务的按钮会高亮显示，再次点击会停止。

`RID`是纯数字，一般从直播间链接中获得。

|                平台                |           `<RID>` 位置            |
| :--------------------------------: | :-------------------------------: |
| [B 站](https://live.bilibili.com/) | `https://live.bilibili.com/<RID>` |
|  [抖音](https://live.douyin.com/)  |  `https://live.douyin.com/<RID>`  |

目前没有进行大量测试，如果有任何建议和问题欢迎提Issues。

## 编译
请参考CI/CD工作流

## 相关项目
- [KuRo_Scanner](https://github.com/Theresa-0328/KuRo_Scanner) – 鸣潮扫码器

## 参考和感谢
- [HonkaiScanner](https://github.com/HonkaiScanner)

- [BililiveRecorder/BililiveRecorder](https://github.com/BililiveRecorder/BililiveRecorder)

- [DGP-Studio/Snap.Hutao](https://github.com/DGP-Studio/Snap.Hutao)
