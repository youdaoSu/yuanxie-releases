# 远协 · 客户端下载

[下载当前稳定版](https://github.com/youdaoSu/yuanxie-releases/releases/latest) · [查看历史版本](https://github.com/youdaoSu/yuanxie-releases/releases)

此仓库只提供安装包、SHA-256 校验文件、下载说明和安装包转存工作流。应用源码保持私有。

## 先选择你的系统

当前默认发布批次为 **v0.19.5**，包含 **Windows x64、Linux x64 的桌面 0.11.9**。这个批次没有 Mac 或 Linux ARM64 安装包，请按下表选择对应入口，不要下载其他系统的文件。

| 电脑 | 下载入口 | 选择的附件 |
| --- | --- | --- |
| Windows，Intel／AMD 64 位 | [当前稳定批次 v0.19.5](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.19.5) | `YuanXie-Desktop-0.11.9-Windows-x64.zip` |
| Ubuntu／Debian，Intel／AMD 64 位 | [当前稳定批次 v0.19.5](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.19.5) | `YuanXie-Desktop-0.11.9-Linux-x64.deb` |
| 其他 Linux，Intel／AMD 64 位 | [当前稳定批次 v0.19.5](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.19.5) | `YuanXie-Desktop-0.11.9-Linux-x64.tar.gz` |
| Mac，Apple M 系列芯片 | [旧版下载 v0.19.0，桌面 0.11.1](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.19.0) | `YuanXie-Desktop-0.11.1-macOS-arm64.dmg` |
| Mac，Intel 芯片 | [旧版下载 v0.19.0，桌面 0.11.1](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.19.0) | `YuanXie-Desktop-0.11.1-macOS-x64.dmg` |
| Linux，ARM64／aarch64 | [旧版下载 v0.19.0，桌面 0.11.1](https://github.com/youdaoSu/yuanxie-releases/releases/tag/v0.19.0) | `YuanXie-Desktop-0.11.1-Linux-arm64.deb` 或 `.tar.gz` |

旧版入口仅用于仍需这些平台安装包的用户，不表示它包含 Windows 新版的全部修正。较早批次的发布标签和桌面版本号不同，请以附件名称、应用设置中的版本号为准。0.20.0 正在本地构建与验收，尚未统一公开发布。

GitHub 自动生成的 **Source code (zip)／Source code (tar.gz) 不是远协安装包**，无需下载。

## 安装与权限

- **Windows：**完整解压 ZIP 后运行其中的 YuanXie 程序，不要直接从压缩包中启动。更新前保存工作并正常退出旧客户端。
- **Mac：**需要 macOS 13 或更新版本。打开对应芯片的 DMG，将 `YuanXie.app` 拖入“应用程序”。这些旧包使用 ad-hoc 签名，未经 Apple Developer ID 签名或公证；首次打开可能需要在系统“隐私与安全性”中确认。麦克风、摄像头和屏幕录制需要分别授权给实际使用的客户端或浏览器。
- **Linux：**Ubuntu／Debian 使用对应架构的 DEB；其他发行版可解压 TAR.GZ。Wayland 的屏幕共享与全局快捷键还取决于桌面门户支持。
- **手机／平板：**使用浏览器打开有效的面板邀请链接；这里没有 Android／iOS 原生安装包。

桌面客户端和浏览器都需要连接可用的远协服务器。下载安装包不会自动创建服务器或账号；邀请链接所属服务器不可用时，应联系邀请者核对当前入口。

## 更新、校验和平台差异

旧版 Windows 可在应用内检查更新；这里列出的旧版 Mac／Linux 客户端可能跳转到下载页，需要手动替换应用或安装新版 DEB。更新时保留原用户配置目录，不删除账号、录制或本地数据。

每个安装包都附有同名 `.sha256` 校验文件。请从本仓库 Release 下载，不使用来源不明的重新打包文件；下载中断可重试，实际速度取决于访问 GitHub 下载线路的网络情况。

Windows 的窗口捕获保护与 Mac／Linux 的能力不同。透明、隐藏、Dock／任务栏不显示，不代表第三方会议一定捕获不到窗口；Mac／Linux 旧包不提供通用的第三方捕获排除保证。请在另一台设备的接收画面中确认实际结果。

这里不发布开发机数据库、账号、API 密钥、录音或私有应用源码。当前可用旧包会保留，待统一新版构建、实机验证和上线完成后再整理过时下载。
